<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view/>
</template>

<script lang="ts">
  import { Options, Vue } from 'vue-class-component';

  @Options({
    
  })
  export default class App extends Vue {
    isInit = false;
    async created() {
      this.isInit = true;
    }
  }
</script>


<style lang="scss">

</style>
