<template>
  <div class="bg-red-700 min-h-screen text-white">
    <NavBar />
    <router-view />
  </div>
</template>

<script>
import NavBar from './components/NavBar'
export default {
  name: 'App',
  components: {
    NavBar
  }
}
</script>
