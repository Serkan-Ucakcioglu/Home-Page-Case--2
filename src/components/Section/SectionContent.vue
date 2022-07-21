<script setup lang="ts">
import SectionCard from "./SectionCard.vue";
</script>
<template>
  <section>
    <div class="container">
      <!-- Content -->
      <div class="content">
        <!-- Content Head  -->
        <div class="head">
          <div class="cover" style="background: rgb(28, 27, 89)"></div>
          <img
            src="https://media.kommunity.com/communities/tracikkaynak/19055/acik-kaynak-platformu.jpg?p=avatar-120"
            alt=""
          />
        </div>

        <!-- Wrapper -->
        <div class="wrapper">
          <div class="title">
            <h1>Türkiye Açık Kaynak Platformu</h1>
            <span>Istanbul • 12137 üyeler</span>
          </div>
          <div class="submit">
            <button>Topluluğa Katıl</button>
          </div>
        </div>
      </div>
      <!-- component -->
      <SectionCard />
    </div>
  </section>
</template>
<style lang="scss" scoped>
section {
  .container {
    .content {
      height: 200px;
      margin-bottom: 15px;
      .head {
        position: relative;
        .cover {
          height: 100px;
          border-radius: 8px;
          margin-top: 25px;
          position: relative;
        }
        img {
          position: absolute;
          top: 70%;
          border-radius: 4px;
          margin-left: 40px;
          height: 130px;
        }
      }
      .wrapper {
        display: flex;
        justify-content: space-between;
        .title {
          width: 60%;
          display: flex;
          flex-direction: column;
          align-items: center;
          margin-top: 15px;

          h1 {
            display: inline;
            font-size: 24px;
            font-weight: bold;
            margin-left: 20px;
          }
          span {
            display: inline;
            color: gray;
            font-size: 15px;
            margin-bottom: 50px;
          }
        }
        .submit {
          display: flex;
          justify-content: flex-end;
          height: 50px;
          margin-top: 20px;
          margin-bottom: 40px;
          button {
            background-color: #38c172;
            border: 1px solid #38c172;
            padding: 8px 26px;
            color: white;
            border-radius: 4px;
            cursor: pointer;
          }
        }
      }
    }
  }
}

@media only screen and (max-width: 800px) {
  .content {
    display: flex;
    flex-direction: column !important;
    // Head
    .head {
      position: relative;
      .cover {
        height: 90px !important;
        border-radius: 8px;
        margin-top: 25px;
        position: relative;
      }
      img {
        position: absolute;
        top: 70%;
        border-radius: 4px;
        margin-left: 10px !important;
        height: 100px !important;
      }
    }

    //   Wrapper
    .wrapper {
      flex-direction: column !important;
      align-items: center !important;
      .title {
        width: 100%;
        margin-left: 0 !important;
        align-items: center;
        justify-content: center;
        text-align: center;
        margin-left: 18px !important;
      }
      .submit {
        margin-top: -30px !important;
        height: 40px !important;
        align-items: center !important;
        margin-bottom: 20px !important;
      }
    }
  }
}
</style>
