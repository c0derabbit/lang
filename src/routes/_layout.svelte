<script>
  import Nav from '../components/nav.svelte';

  export let segment;
</script>

<style>
  main {
    max-width: 1080px;
    background-color: white;
    padding: 2em;
    margin: 0 auto;
    box-sizing: border-box;
  }
</style>

<Nav {segment} />

<main>
  <slot></slot>
</main>
