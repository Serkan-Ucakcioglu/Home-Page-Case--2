<script setup lang="ts"></script>
<template>
  <section>
    <div class="container">
      <div class="content">
        <div class="head">
          <div class="cover" style="background: rgb(28, 27, 89)"></div>
          <img
            src="https://media.kommunity.com/communities/tracikkaynak/19055/acik-kaynak-platformu.jpg?p=avatar-120"
            alt=""
          />
        </div>
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
    </div>
  </section>
</template>
<style lang="scss">
section {
  .container {
    .content {
      height: 200px;
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
          display: flex;
          flex-direction: column;
          align-items: flex-start;
          margin-left: 250px;
          h1 {
            display: inline;
            font-size: 24px;
            font-weight: bold;
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
</style>
