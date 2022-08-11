<script setup>
// import HelloWorld from "./components/HelloWorld.vue";
// import TheWelcome from "./components/TheWelcome.vue";
import CookieStand from "./components/CookieStand.vue";
</script>

<template>
  <body class="app">
    <!-- <header>
    <img
      alt="Vue logo"
      class="logo"
      src="./assets/logo.svg"
      width="225"
      height="125"
    />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header> -->

    <main>
      <CookieStand />
    </main>

    <!-- <main>
    <TheWelcome />
  </main> -->
  </body>
</template>

<style scoped>
.app {
  width: 90vw;
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding-bottom: 15px;
}
</style>
