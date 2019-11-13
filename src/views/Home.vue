<template>
  <div class="home">
    <img alt="logo" src="../assets/logo.png">
    <MyComp msg="Bem vindo! Este e o Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import MyComp from '@/components/MyComp.vue'

export default {
  name: 'home',
  components: {
    MyComp
  }
}
</script>
