<script setup lang="ts"></script>
<template>
  <section>
    <div class="container">
      <div class="head">
        <div class="cover" style="background: rgb(28, 27, 89)"></div>
        <img
          src="https://media.kommunity.com/communities/tracikkaynak/19055/acik-kaynak-platformu.jpg?p=avatar-120"
          alt=""
        />
      </div>
    </div>
  </section>
</template>
<style lang="scss">
section {
  .container {
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
        top: 50%;
        border-radius: 4px;
        margin-left: 40px;
        height: 130px;
      }
    }
  }
}
</style>
