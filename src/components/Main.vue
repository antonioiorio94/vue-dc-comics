<template>
  <main>
    <div>
      <div class="container">
        <ComicsItem
          v-for="(item, index) in Comics"
          :key="index"
          :comic="item"
        />
      </div>
    </div>
  </main>
</template>

<script>
import ComicsItem from "@/components/ComicsItem.vue";

export default {
  name: "mainComponent",
  props: {
    Comics: Array,
  },
  components: { ComicsItem },
};
</script>

<style lang="scss" scoped>
main {
  background-color: #1c1c1c;
  div {
    padding: 50px;
    color: white;
    .container {
      display: flex;
      flex-wrap: wrap;
    }
  }
}
</style>
