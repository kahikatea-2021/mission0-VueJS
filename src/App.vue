<script setup>
import HeaderPage from "./components/HeaderPage.vue";
import SearchSection from "./components/SearchSection.vue";
import "./assets/main.css";
</script>

<template>
  <div>
    <header>
      <div>
        <HeaderPage />
      </div>
    </header>

    <main>
      <div>
        <SearchSection />
      </div>
    </main>
  </div>
</template>
