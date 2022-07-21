<script lang="ts" setup></script>

<template>
  <header>
    <div class="container">
      <div class="list">
        <div class="logo">
          <img
            src="https://kommunity.com/img/logo.svg"
            width="180"
            height="21"
            loading="lazy"
            alt=""
          />
        </div>
        <nav class="nav-list">
          <a href="#">Anasayfa</a>
          <a href="#">Hakkımızda</a>
          <a href="#">Forum</a>
          <a href="#">Neden Biz ? </a>
          <a href="#">Sponsorlar</a>
        </nav>
      </div>
      <div class="login">
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
  height: 80px;
  .container {
    display: flex;
    justify-content: space-between;
    .list {
      display: flex;
      height: 80px;
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
  
}


</style>
