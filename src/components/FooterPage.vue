<template>
    <footer>
        <div class="bc-cb">
            <div class="img1">
                <img src="img/buy-comics-digital-comics.png" alt="">
                <div class="text1">DIGITAL COMICS</div>
            </div>
            <div class="img1">
                <img src="img/buy-comics-merchandise.png" alt="">
                <div class="text1">DC MERCHANDISE</div>
            </div>
            <div class="img1">
                <img src="img/buy-comics-subscriptions.png" alt="">
                <div class="text1">SUBSCRIPTION</div>
            </div>
            <div class="img1">
                <img src="img/buy-comics-shop-locator.png" alt="">
                <div class="text1">COMIC SHOP LOCATOR</div>
            </div>
            <div class="img1">
                <img src="img/buy-dc-power-visa.svg" alt="">
                <div class="text1">DC POWER VISA</div>
            </div>
        </div>
        <div class="bg-img">
            <div class="text-col">

            </div>
            <div class="cont-img">

            </div>
        </div>
    </footer>
  </template>
  
  <script>
  export default {
    name: 'FooterPage',
  };
  </script>
  
  <style lang="scss" scoped>
    
    .bc-cb{
        background-color: #0282F9;
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 2rem;
        height: 150px;
        color: white;
    }
    .img1{
        margin: 1rem;
        height: 50px;
        width: 250px;
        display: flex;
        text-align: center;
        justify-content: center;
        align-items: center;
        gap: 1rem;
    }
    img{
        height: 50px;
    }
    .bg-img{
        height: 6rem;
        background-image: url('img/footer-bg.jpg');
        background-position: top;
        background-repeat: no-repeat;
        background-size: cover;
        display: flex;
        justify-content: space-between;
    }
    
  </style>