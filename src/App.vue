<template>
  <div id="q-app">
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>
<style>
   .hov{
        transition: color 0.2s ease-out;
    }
    
    .hov:hover{
        color: red;
    }
    .footer-link{
        transition: color 0.2s ease-out;
    }
    
    .footer-link:hover{
        color: red;
    }
</style>
