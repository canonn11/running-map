<script>
  import Router from "svelte-spa-router";
  import About from "./About.svelte";
  import Home from "./Home.svelte";
</script>

<main>
  <a href="/">홈</a>
  <a href="/#/About">어바웃12</a>
</main>

<Router
  routes={{
    "/": Home,
    "/about": About,
  }}
/>