<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <Quote>
            <h2 slot="title">{{ quoteTitle }}</h2>
            <p>A wonderful Quote</p>
          </Quote>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Quote from "./components/Quote.vue";

export default {
  name: "app",
  components: {
    Quote,
    // HelloWorld
  },
  data() {
    return {
      quoteTitle: "The Quote",
    };
  },
};
</script>

<style>
</style>
