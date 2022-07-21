<script lang="ts" setup>
import { ref } from "@vue/reactivity";

let isShow = ref<boolean>(false);
</script>

<template>
  <header>
    <div class="container">
      <div class="list">

        <!-- head -->
        <div class="head">
          <!-- logo img  -->
          <div class="logo">
            <img
              src="https://kommunity.com/img/logo.svg"
              width="180"
              height="21"
              loading="lazy"
              alt=""
            />
          </div>
          <!-- responsive hamburger btn  -->
          <div class="hamburger-btn" @click="isShow = !isShow">
            <svg
              class="open-menu"
              v-show="isShow == false"
              viewBox="0 0 100 80"
              width="25"
              height="25"
            >
              <rect width="100" height="20"></rect>
              <rect y="30" width="100" height="20"></rect>
              <rect y="60" width="100" height="20"></rect>
            </svg>
            <svg
              v-show="isShow == true"
              class="close-menu"
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
            >
              <path
                d="M24 20.188l-8.315-8.209 8.2-8.282-3.697-3.697-8.212 8.318-8.31-8.203-3.666 3.666 8.321 8.24-8.206 8.313 3.666 3.666 8.237-8.318 8.285 8.203z"
              />
            </svg>
          </div>
          <!-- head  -->
        </div>

        <!-- nav link header  -->
        <nav :class="{active: isShow}" class="nav-list">
          <a href="#">Anasayfa</a>
          <a href="#">Hakkımızda</a>
          <a href="#">Forum</a>
          <a href="#">Neden Biz ? </a>
          <a href="#">Sponsorlar</a>
        </nav>
      </div>
<!-- login buttons header  -->
      <div :class="{active: isShow}" class="login">
        <button class="login-btn btn">Giriş Yap</button>
        <button class="register-btn btn">Üye Ol</button>
      </div>
    </div>
  </header>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
header {
  -webkit-box-shadow: 0 2px 4px 0 rgb(26 30 33 / 7%);
  box-shadow: 0 2px 4px 0 rgb(26 30 33 / 7%);
  min-height: 80px;
  .container {
    display: flex;
    justify-content: space-between;
    .hamburger-btn {
      display: none;
    }
    .list {
      display: flex;
      min-height: 80px;
      align-items: center;
      .logo {
        display: flex;
        align-items: center;
        height: 80px;
      }
      .nav-list {
        margin-left: 25px;
        a {
          font-size: 15px;
          color: #6e7880;
          padding: 0px 5px;
        }
      }
    }
  }

  //login
  .login {
    display: flex;
    height: 80px;
    align-items: center;
    .btn {
      display: inline;
      height: 50px;
      line-height: 48px;
      padding: 0 30px;
      font-size: 16px;
      font-weight: 500;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    .login-btn {
      background-color: #1a1e21;
      border: 1px solid #1a1e21;
      color: white;
      margin-right: 5px;
    }
    .register-btn {
      background-color: #ffbc00;
      border: 1px solid #ffbc00;
      color: white;
    }
  }
}
//responsive
@media only screen and (max-width: 800px) {
  .container {
    flex-direction: column;
    .list {
      width: 100%;
      flex-direction: column !important;
      align-items: center !important;
      justify-content: space-between;
      .head {
        width: 100%;
        display: flex;
        justify-content: space-between !important;
        .hamburger-btn {
          height: 80px;
          display: flex !important;
          justify-content: flex-end;
          align-items: center;
        }
        .logo {
          display: flex;
        }
      }

      .nav-list {
        width: 100% !important;
        display: none ;
        flex-direction: column !important;
        align-items: center !important;
        justify-content: center !important;
        text-align: center;
        margin: 0 !important;
        a {
          width: 100%;
          display: block;
          text-align: center;
          border: 1px solid black;
          border-radius: 4px;
          margin-bottom: 10px;
          padding: 5px 0px !important;
        }
      }
    }
    .login {
      display: none ;
      justify-content: center !important;
    }
  }
}

.active{
  display: flex !important;
}
</style>
