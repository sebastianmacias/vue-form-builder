<template>
<ion-page>
<navbar></navbar>
<router-view></router-view>
</ion-page>
</template>

<script>
import 'vue-router'
import Navbar from './Navbar'

export default {
  data () {
    return {
    }
  },

  computed: {
  },

  methods: {
  },

  mounted () {
  },

  components: {
    'navbar': Navbar
  }
}
</script>

<style>
ion-page,
ion-content {
  height: 100vh;
}
</style>