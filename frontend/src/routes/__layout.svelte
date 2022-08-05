<script lang="ts">
  // design
  import '$lib/design/design.scss';
  // components
  import Header from "$lib/components/layout/Header.svelte";
</script>

<header>
  <Header/>
</header>

<main>
  <slot/>
</main>