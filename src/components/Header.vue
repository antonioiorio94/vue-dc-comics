<template>
  <header>
    <!-- Logo -->
    <div>
      <img src="@/assets/dc-logo.png" alt="Dc-Logo" />
    </div>

    <!-- Navbar -->
    <div>
      <ul>
        <li v-for="item in navLinks" :key="item">{{ item }}</li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: "headerComponent",
  props: { navLinks: Array },
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
