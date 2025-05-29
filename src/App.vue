<script setup lang="ts">
import TopBanner from './components/TopBanner.vue'
import TheWelcome from './components/PortfolioBody.vue'
</script>

<template>
  <header>
    <!-- <img alt="Rolando Rodriguez" class="logo" src="./assets/rolando.jpg" /> -->
    <div class="wrapper">
      <TopBanner msg="Rolando Rodriguez" />
    </div>
  </header>

  <main>
    <hr />
    <TheWelcome />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
    display: flex;
  }

  .logo {
    margin: 0 2rem 0 0;
    max-width: 150px;
    max-height: 150px;
    border-radius: 10px;
  }
}
</style>
