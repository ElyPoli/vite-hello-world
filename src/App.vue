<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  components: {
    AppTitle,
    AppHero,
  }
}
</script>

<template>
  <main class="vh-100">
    <AppHero></AppHero>
    <AppTitle></AppTitle>
  </main>
</template>

<style></style>
