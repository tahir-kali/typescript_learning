<template>
 <div>
  <div class="header text-white px-10 py-5 text-center bg-green-500">
    Welcome to Learning <span class="logo">.nGlish</span> with Rahimi
 </div>
 </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage'
})
</script>
<style>
.header{
  font-size: 30px
}
.logo{
  padding:10px;
  border: 1px solid black;
  border-radius: 15px;
  background-color: black !important;
}
</style>