<script lang="ts">
  import Facebook from "$lib/icons/Facebook.svelte";
  import Twitter from "$lib/icons/Twitter.svelte";
  import Youtube from "$lib/icons/Youtube.svelte";
  import Instagram from "$lib/icons/Instagram.svelte";
  import ChevronRight from "$lib/icons/ChevronRight.svelte";
</script>

<svelte:head>
  <title>Stella Ndizye | Fashion model - Content creator - Enterpreneur.</title>
</svelte:head>

<div class="header">
  <strong class="header__logo">
    <a href="/">stella ndizye</a>
  </strong>

  <div class="header__chevron">
    <ChevronRight/>
  </div>

  <nav class="header__nav">
    <a href="/">Home</a>
    <a href="/collections">Collections</a>
    <a href="/blog">Blog</a>
  </nav>

  <ul class="header__socials">
    <li>
      <a href="https://twitter.com" target="_blank"><Twitter/></a>
    </li>
    <li>
      <a href="https://youtube.com" target="_blank"><Youtube/></a>
    </li>
    <li>
      <a href="https://facebook.com" target="_blank"><Facebook/></a>
    </li>
    <li>
      <a href="https://instagram.com" target="_blank"><Instagram/></a>
    </li>
  </ul>
</div>