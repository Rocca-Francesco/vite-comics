<script>
export default {
  props: {
    comicsList: Array,
  }
}
</script>

<template>
  <main>
    <jumbotron>
    </jumbotron>

    <section id="lastComics">
      <div v-for="comics in comicsList">
        <img :src="comics.thumb" alt="">
        <h4>{{ comics.series }}</h4>
      </div>
    </section>

    <section id="shoppingZone">
      <div>
        <img src="/shopping-area/buy-comics-digital-comics.png" alt="digital-comics">
        <span>DIGITAL COMICS</span>
      </div>
      <div>
        <img src="/shopping-area/buy-comics-merchandise.png" alt="comics-merchandise">
        <span>DC MERCHANDISE</span>
      </div>
      <div>
        <img src="/shopping-area/buy-comics-shop-locator.png" alt="comics-shop-locator">
        <span>SUBSCRIPTION</span>
      </div>
      <div>
        <img src="/shopping-area/buy-comics-subscriptions.png" alt="comics-subscriptions">
        <span>COMIC SHOP LOCATOR</span>
      </div>
    </section>
  </main>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/mixins.scss" as *;
@use "../assets/scss/partials/variables.scss" as *;


jumbotron {
  background-image: url(../../public/jumbotron.jpg);
  display: block;
  height: 15rem;
  background-repeat: no-repeat;
  background-size: cover;
}

#lastComics {
  @include alignCenter ();
  flex-wrap: wrap;

  padding: 1rem 3rem;

  background-color: #1c1c1c;
  font-weight: bold;
  color: white;

  div {
    width: calc(100%/6);

    img {
      width: 3rem;
    }


  }
}

#shoppingZone {
  height: 5rem;
  padding: 1rem 3rem;
  @include alignCenter ();

  background-color: $blueDC;
  font-weight: bold;
  color: white;

  div {
    display: flex;
    align-items: center;

    img {
      width: 3rem;
      padding: 0.5rem;
    }
  }
}
</style>