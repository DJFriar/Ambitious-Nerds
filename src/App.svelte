<script>
  import Header from './components/Header.svelte';
  import Footer from './components/Footer.svelte';
</script>

<Header />

<main>
	<p>We are nerds. We are ambitious. We are...</p>
	<h1>Ambitious Nerds, LLC</h1>
  <p>We build software applications and web sites.</p>
  <p class="tiny-text">Except this one, it seems. Don't worry, this is just a placeholder while we finish up the real one.</p>
</main>

<Footer />

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #863084;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}

  .tiny-text {
    font-size: 8px;
  }
</style>