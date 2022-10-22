<template>
  <div>
    <hello-world/>
    <main-page/>
  </div>
</template>

<script>
  import HelloWorld from '../components/HelloWorld'
  import MainPage from '../components/MainPage.vue'

  export default {
    name: 'HomeView',

    components: {
      HelloWorld,
      MainPage,
    },
  }
</script>
