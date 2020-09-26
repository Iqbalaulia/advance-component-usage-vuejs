
<template>
  <div id="quote">
    <!-- Passing component tag html from parent to child use slot  -->
    <slot></slot>
  </div>
</template>

<script>
export default {
  props: ["quote"],
  name: "quote",
  data() {
    return {};
  },
  methods: {},
};
</script>

<style scoped>
div {
  border: 1px solid #cccccc;
  box-shadow: 1px 1px 2px black;
  padding: 30px;
  margin: 30px auto;
  text-align: center;
}

/* styling must be on child component */
h2 {
  color: red;
}
</style>