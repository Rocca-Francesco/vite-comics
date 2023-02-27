<script>
</script>

<template>
  <footer>
    <section id="footerLinks">
      <div>
        <h2>DC COMICS</h2>
        <ul>
          <li>Characters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>TV</li>
          <li>Games</li>
          <li>Video</li>
          <li>News</li>
        </ul>

        <h2>SHOP</h2>
        <ul>
          <li>Shop DC</li>
          <li>Shop DC Collecticables</li>
        </ul>
      </div>

      <div>
        <h2>DC</h2>
        <ul>
          <li>Terms Of Use</li>
          <li>Privacy policy (New)</li>
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

      <div>
        <h2>SITES</h2>
        <ul>
          <li>DC</li>
          <li>MAD Magazine</li>
          <li>DC Kids</li>
          <li>DC Universe</li>
          <li>DC Power VISA</li>
        </ul>
      </div>
    </section>


    <section id="utilsSocials">
      <button type="button">SIGN-UP NOW!</button>
      <div>
        <span>FOLLOW US</span>
        <span>
          <img src="/footer/footer-facebook.png" alt="facebook">
        </span>
        <span>
          <img src="/footer/footer-twitter.png" alt="twitter">
        </span>
        <span>
          <img src="/footer/footer-youtube.png" alt="youtube">
        </span>
        <span>
          <img src="/footer/footer-pinterest.png" alt="pinterest">
        </span>
        <span>
          <img src="/footer/footer-periscope.png" alt="periscope">
        </span>
      </div>
    </section>
  </footer>
</template>

<style lang="scss" scoped>
#footerLinks {
  width: calc(100vw - 6rem);
  padding: 1rem 3rem;
  background-image: url(/footer/footer-bg.jpg);
  display: flex;

  div {
    padding: 1rem;
  }

  h2 {
    font-size: 1rem;
    color: white;
  }

  ul {
    list-style: none;
    color: lightgray;
    padding: 0;
  }
}

#utilsSocials {
  width: calc(100vw - 6rem);
  height: 3rem;
  padding: 1rem 3rem;
  display: flex;
  justify-content: space-between;
  align-items: center;

  background-color: grey;

  button {
    background-color: grey;
    border: 2px solid blue;
    padding: 0.4rem;
  }

  div {
    display: flex;
    align-items: center;

    span {
      padding: 0.2rem;
    }
  }
}
</style>