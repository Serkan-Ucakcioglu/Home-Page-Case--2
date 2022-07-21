<script setup lang="ts"></script>

<template>
  <footer>
    <div class="container">
      <div class="head-btn">
        <a  href="#" class="btn">Etkinlikleri Keşfet</a>
        <a  href="#" class="btns">Topluluğunu Oluştur</a>
      </div>
      <div class="list">
        <ul>
            <li> <h3>KOMMUNITY</h3></li>
            <li>
                <a href="#">Fiyatlandırma</a>
            </li>
            <li>
                <a href="#">Hakkımızda</a>
            </li>
            <li>
                <a href="#">Ekip</a>
            </li>
            <li>
                <a href="#">Destek</a>
            </li>
            <li>
                <a href="#">Gizlilik Politikası</a>
            </li>
            <li>
                <a href="#">Kullanım Koşulları</a>
            </li>
            <li>
                <a href="#">GDPR</a>
            </li>
            <li>
                <a href="#">
                    Durum Sayfası
                </a>
            </li>
        </ul>
         <ul>
            <li> <h3>KOMMUNITY</h3></li>
            <li>
                <a href="#">Fiyatlandırma</a>
            </li>
            <li>
                <a href="#">Hakkımızda</a>
            </li>
            <li>
                <a href="#">Ekip</a>
            </li>
            <li>
                <a href="#">Destek</a>
            </li>
            <li>
                <a href="#">Gizlilik Politikası</a>
            </li>
            <li>
                <a href="#">Kullanım Koşulları</a>
            </li>
            <li>
                <a href="#">GDPR</a>
            </li>
            <li>
                <a href="#">
                    Durum Sayfası
                </a>
            </li>
        </ul>
         <ul>
            <li> <h3>KOMMUNITY</h3></li>
            <li>
                <a href="#">Fiyatlandırma</a>
            </li>
            <li>
                <a href="#">Hakkımızda</a>
            </li>
            <li>
                <a href="#">Ekip</a>
            </li>
            <li>
                <a href="#">Destek</a>
            </li>
            <li>
                <a href="#">Gizlilik Politikası</a>
            </li>
            <li>
                <a href="#">Kullanım Koşulları</a>
            </li>
            <li>
                <a href="#">GDPR</a>
            </li>
            <li>
                <a href="#">
                    Durum Sayfası
                </a>
            </li>
        </ul>
         <ul>
            <li> <h3>KOMMUNITY</h3></li>
            <li>
                <a href="#">Fiyatlandırma</a>
            </li>
            <li>
                <a href="#">Hakkımızda</a>
            </li>
            <li>
                <a href="#">Ekip</a>
            </li>
            <li>
                <a href="#">Destek</a>
            </li>
            <li>
                <a href="#">Gizlilik Politikası</a>
            </li>
            <li>
                <a href="#">Kullanım Koşulları</a>
            </li>
            <li>
                <a href="#">GDPR</a>
            </li>
            <li>
                <a href="#">
                    Durum Sayfası
                </a>
            </li>
        </ul>
         <ul>
            <li> <h3>KOMMUNITY</h3></li>
            <li>
                <a href="#">Fiyatlandırma</a>
            </li>
            <li>
                <a href="#">Hakkımızda</a>
            </li>
            <li>
                <a href="#">Ekip</a>
            </li>
            <li>
                <a href="#">Destek</a>
            </li>
            <li>
                <a href="#">Gizlilik Politikası</a>
            </li>
            <li>
                <a href="#">Kullanım Koşulları</a>
            </li>
            <li>
                <a href="#">GDPR</a>
            </li>
            <li>
                <a href="#">
                    Durum Sayfası
                </a>
            </li>
        </ul>
      </div>
      
      <div class="title">
        <span style="color: gray;">© 2022 Kommunity, Inc. 548 Market St. 94104 SF, CA</span>
      </div>

      <div class="store">
        <img src="https://kommunity.com/img/ios.png" alt="">
        <img src="https://kommunity.com/img/android.png" alt="">
      </div>
    </div>
  </footer>
</template>

<style scoped lang="scss">
footer {
  min-height: 600px;
  background: black;
  display: flex;
  justify-content: center;

  .head-btn {
    display: flex;
    justify-content: center;
    margin-top: 70px;
    border-bottom: 1px solid gray;
    a{
   display: block;
    height: 50px;
    text-align: center;
    line-height: 50px;
    border-radius: 4px;
    font-size: 16px;
    font-weight: 700;
    margin-bottom: 20px;
    text-decoration: none;
    width: 40%;
    border: none;
    cursor: pointer;
    margin-left: 10px;
    }
    .btn {
      background: #ffbc00;
      color: white;
    }
    .btns {
      background-color: #fff;
      color: #000;
    }
  }
  .list{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    margin-top: 40px;
    ul{
    display: flex;
    flex-direction: column;
    justify-content: center;
    li{
        display: flex;
        flex-direction: column;
        h3{
            color: white;
        }
        a{
            color: gray;
            font-size: 15px;
        }
    }
  }
  }
  .title{
    margin-top: 30px;
    justify-content: center;
  }
  .store{
    display: flex;
    justify-content: flex-end;
    margin-top: 20px;
   img{
     width: 100px;
    height: 48px;
   }
  }
}
@media only screen and (max-width: 800px) {
  .head-btn {
  
    a{
   
    font-size: 10px !important;
    font-weight: 700;
    margin-bottom: 20px;
    text-decoration: none;
    width: 40%;
    border: none;
    cursor: pointer;
    margin-left: 10px;
    }
   
  }
}
</style>
