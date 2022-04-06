<template>
  <footer>
    <!--Banner-->
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
    <!--Sezione link-->
    <div class="link-section">
      <div class="link-container">
        <div class="col">
          <ul>
            <h3>DC COMICS</h3>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
          </ul>
          <ul>
            <h3>SHOP</h3>
            <li>Shop DC</li>
            <li>Shop DC Collectibles</li>
          </ul>
        </div>
        <div class="col">
          <ul>
            <h3>DC</h3>
            <li>Terms of use</li>
            <li>Privacy Policy</li>
            <li>Ad Choices</li>
            <li>Advertising</li>
            <li>Jobs</li>
            <li>Subscriptions</li>
            <li>Talent Workshops</li>
            <li>CPSC Certificates</li>
            <li>Ratings</li>
            <li>Shop Help</li>
            <li>Contact Us</li>
          </ul>
        </div>
        <div class="col">
          <ul>
            <h3>SITES</h3>
            <li>DC</li>
            <li>MAD MAgazines</li>
            <li>DC Kids</li>
            <li>DC Universe</li>
            <li>DC Power Visa</li>
          </ul>
        </div>
        <div class="footer-logo">
          <img src="../assets/dc-logo-bg.png" alt="logo" />
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

.link-section {
  background-image: url(../assets/footer-bg.jpg);
  background-size: cover;
  display: flex;

  .link-container {
    width: 70%;
    margin: 0 auto;
    display: flex;
    padding: 2rem;

    ul {
      list-style-type: none;
      color: #fff;
      li {
        color: rgb(122, 122, 122);
      }
    }
  }
}
</style>
