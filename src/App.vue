<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view />
</template>

<script lang="ts">
import "@/styles.css";
import { Vue } from "vue-class-component";

export default class App extends Vue {}
</script>
