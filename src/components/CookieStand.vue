<script setup>
import Sales from "./Sales.vue";
</script>
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Akshar:wght@300&display=swap" />

<template>
  <h1 class="highlights">Salmon Cookies</h1>
  <img src="img/salmon.png" width="600" />
  <nav class="text">
    <ul>
      <li><a href="sales.html">Sales</a></li>
    </ul>
  </nav>
  <section class="center">
    <div>
      <img src="img/chinook.jpg" alt="Chinook fish" height="250" width="300" />
    </div>

    <div>
      <img
        src="img/cutter.jpeg"
        alt="Fish cookie cutter"
        height="250"
        width="300"
      />
    </div>
  </section>

  <section>
    <div>
      <Sales />
    </div>

    <section class="center">
      <div>
        <img
          src="img/family.jpg"
          alt="stock photo of family at table with cookies and milk"
          height="250"
          width="300"
        />
      </div>
      <div>
        <img
          src="img/fish.jpg"
          alt="animated salmon"
          height="250"
          width="300" />
      </div>
    </section>

    <div>
      <ul class="text">
        Hours
        <li>Monday thru Saturday - 6am to 8pm</li>
        <li>Sunday - Closed</li>
      </ul>
    </div>

    <section class="center">
      <div>
        <img
          src="img/frosted-cookie.jpg"
          alt="frosted salmon decorated cookie"
          height="250"
          width="300"
        />
      </div>
      <div>
        <img src="img/shirt.jpg" alt="shirt" height="250" width="300" />
      </div>
    </section>

    <div>
      <ul class="text">
        Contact Us
        <li>cookiestandemail@cookiestand.com</li>
        <li>000-867-5309</li>
      </ul>
    </div>
  </section>
</template>

<style scoped>
template {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.highlights {
  font-family: "Akshar", sans-serif;
}
.text {
  font-family: Georgia, "Times New Roman", Times, serif;
}
.center {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
</style>
