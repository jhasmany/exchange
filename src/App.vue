<template>
  <main>
    <header-custom/>
    <router-view class="container px-5 sm:px-20 py-20 flex justify-center" />
    <div class="footer">Proyecto desarrollado por Jhasmany Roque Chambi en el curso de Vue en Platzi!</div>
  </main>
</template>

<script>
import HeaderCustom from '@/components/HeaderCustom'

export default {
  name: 'app',
  components: { HeaderCustom },
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.footer{
  text-align: center;
}
</style>
