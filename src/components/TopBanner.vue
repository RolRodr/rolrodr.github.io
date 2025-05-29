<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="bannerWrapper">
    <div class="greetings">
      <h1 class="green">{{ msg }}</h1>
      <p>
        Data librarian, <br />
        Software developer, <br />
        but mainly a people person. <br />
      </p>
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

p {
  font-size: 1.2rem;
}

.greetings h1,
.greetings p {
  text-align: center;
  margin-left: 1rem;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings p {
    text-align: left;
  }
}
</style>
