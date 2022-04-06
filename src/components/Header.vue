<template>
  <header>
    <!-- Logo -->
    <div>
      <img src="../assets/dc-logo.png" alt="Dc-Logo" />
    </div>

    <!-- Navbar -->
    <div>
      <ul>
        <li>Characters</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>TV</li>
        <li>Games</li>
        <li>Collectibles</li>
        <li>Videos</li>
        <li>Fans</li>
        <li>News</li>
        <li>Shop</li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: "headerComponent",
};
</script>

<style lang="scss" scoped>
header {
  display: flex;
  align-items: center;
  justify-content: space-around;
  font-weight: bolder;
  padding: 2rem;
}

ul {
  display: flex;
  list-style-type: none;
  text-transform: uppercase;
  color: rgb(53, 53, 53);

  li {
    padding: 10px;
  }
}
</style>
