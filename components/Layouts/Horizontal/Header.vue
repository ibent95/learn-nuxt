<script lang="ts"></script>

<style lang="scss" scoped>
header {
  background-color: #F3EDC8; // #05c46b
  padding: 10px 0;
}

div.brand-logo {
  img {
    height: 44px;
  }
  span.brand-name {
    padding-left: 10px;
  }
}

li {
  margin: 10px 10px;
}
</style>

<template>
  <header>

    <div class="container mx-auto flex justify-between">

      <div class="brand-logo flex align-center">
        <img class="brand-logo-img" src="@/assets/img/brand-logo-green.png" alt="Ibent95">
        <span class="brand-name">Ibent95</span>
      </div>

      <div class="flex menu-list">
        <ul class="flex">
          <li>
            <NuxtLink to="/">Beranda</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/services">Layanan</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/about">Tentang</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/auth/login">Masuk</NuxtLink>
          </li>
        </ul>
      </div>

    </div>

  </header>
</template>
