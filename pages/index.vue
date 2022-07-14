<template>
  <main>
    <AppBar/>
    <router-view></router-view>
    <section 
    class="bg-cover bg-black h-screen"
    style="background-image: url('https://images.ctfassets.net/wn7ipiv9ue5v/3XvPIRrEsjF3xpeKArg6CN/7b5ed496b02c8f57732dbf625d108a5e/bioshock-tc_keyart_L_1.jpg');">
    <div 
    class="h-screen bg-black opacity-25"
    ></div>
    </section>
  </main>
</template>

<script>
import AppBarVue from '../components/AppBar.vue'
export default {
  name: 'IndexPage',
  components: [
    "AppBar"
  ]
}
</script>
