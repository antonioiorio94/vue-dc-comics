<template>
  <div class="card">
    <img :src="comic.thumb" alt="" />
    <p>{{ comic.series }}</p>
  </div>
</template>

<script>
export default {
  name: "ComicItem",
  props: {
    comic: Object,
  },
};
</script>

<style lang="scss" scoped>
.card {
  width: calc(100% / 6);
  img {
    max-width: -webkit-fill-available;
    box-shadow: 10px 5px 25px rgba(255, 255, 255, 0.627);
  }
  p {
    text-align: center;
    padding: 1rem;
  }
}
</style>
