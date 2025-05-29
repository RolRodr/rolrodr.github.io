<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="bannerWrapper">  
    <div class="greetings">
      <h1 class="green">{{ msg }}</h1>
      <h3>
        Data librarian, <br>
        Software developer, <br>
        but mainly a people person. <br>
      </h3>
    </div>
  </div>
</template>

<style scoped>
.bannerWrapper {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0.4rem 0 1rem calc(var(--section-gap) / 2);
}

h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
  margin-left: 1rem;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
