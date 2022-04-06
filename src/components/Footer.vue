<template>
  <footer>
    <div class="banner">
      <div class="banner-conteiner">
        <div class="banner-card">
          <img src="../assets/buy-comics-digital-comics.png" alt="buy_comics" />
          <p>DIGITAL COMICS</p>
        </div>
        <div class="banner-card">
          <img src="../assets/buy-comics-merchandise.png" alt="merch_comics" />
          <p>DC MERCHANDISE</p>
        </div>
        <div class="banner-card">
          <img src="../assets/buy-comics-subscriptions.png" alt="shop_comics" />
          <p>SUBSCRIPTION</p>
        </div>
        <div class="banner-card">
          <img src="../assets/buy-comics-shop-locator.png" alt="sub_comics" />
          <p>COMIC SHOP LOCATOR</p>
        </div>
        <div class="banner-card">
          <img src="../assets/buy-dc-power-visa.svg" alt="visa_comics" />
          <p>DC POWER VISA</p>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "footerComponent",
};
</script>

<style lang="scss" scoped>
.banner {
  background-color: #0c7cec;
  padding: 2rem;

  .banner-conteiner {
    width: 70%;
    margin: 0 auto;
    display: flex;
    justify-content: space-evenly;

    .banner-card {
      display: flex;
      align-items: center;

      img {
        width: 3rem;
        padding: 5px;
        margin-right: 10px;
      }

      p {
        color: #fff;
      }
    }
  }
}
</style>
