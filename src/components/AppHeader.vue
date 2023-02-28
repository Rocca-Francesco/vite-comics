<script>
</script>

<template>
  <header>
    <div id="logo">
      <img src="/dc-logo.png" alt="dc-logo">
    </div>
    <div id="navbar">
      <ul>
        <li>CHARACTERS</li>
        <li>COMICS</li>
        <li>MOVIES</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECTIBLES</li>
        <li>VIDEOS</li>
        <li>FANS</li>
        <li>NEWS</li>
        <li>SHOP</li>
      </ul>
    </div>
  </header>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/mixins.scss" as *;

header {
  @include alignCenter ();

  height: 5rem;
  padding: 1rem 3rem;
}

#logo {
  img {
    width: 4rem;
  }
}

#navbar {
  ul {
    display: flex;

    li {
      list-style: none;
      padding: 0.7rem;
      font-size: 0.8rem;
      font-weight: bold;
    }
  }
}
</style>