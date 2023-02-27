<script>
</script>

<template>
  <main>
    <section id="templateProvvisorio">
      <span>Content goes here</span>
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
#templateProvvisorio {
  width: calc(100vw - 6rem);
  height: 5rem;
  padding: 1rem 3rem;
  display: flex;
  justify-content: space-between;
  align-items: center;

  background-color: black;
  font-weight: bold;
  color: white;
}

#shoppingZone {
  width: calc(100vw - 6rem);
  height: 5rem;
  padding: 1rem 3rem;
  display: flex;
  justify-content: space-between;
  align-items: center;

  background-color: cornflowerblue;
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