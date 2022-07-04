<script setup>
import Menu from './components/Menu.vue'
import Corpo from './components/Corpo.vue'
import Blog from './components/Blog.vue'
</script>

<template>
  <header class="flex">
    <div class="container">
      <section>
        <Menu />
        <Corpo />
      </section>
    </div>
  </header>

  <main class="flex">
    <div class="container2">
      <Blog />
    </div>
  </main>
</template>

<style>
#app {
  margin: 0 auto;
  font-weight: normal;
  font-family: system-ui;
  color: white;
}

body {
  margin: 0;
}

header {
  background-color: #2f558d;
  text-align: center;
}

.flex {
  display: flex;
  justify-content: center;
}

main div.container2 {
  max-width: 500px;
  min-width: 500px;
}

header div.container {
  max-width: 1280px;
  min-width: 1000px;
}

main {
  color: black;
}
</style>
