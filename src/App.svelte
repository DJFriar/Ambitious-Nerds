<script>
  import router from 'page';
  import Header from './components/Header.svelte';
  import Footer from './components/Footer.svelte';
  import Portfolio from './components/Portfolio.svelte';
  import YouTube from './components/YouTube.svelte';

  let page;
  router ('/', () => page = Portfolio )
  router('/YouTube', () => page = YouTube)
  router.start()
</script>

<Header />

<svelte:component this={page} />

<Footer />

<style>

</style>