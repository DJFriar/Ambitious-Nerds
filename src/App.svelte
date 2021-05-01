<script>
  import Header from './components/Header.svelte';
  import Footer from './components/Footer.svelte';
  import Portfolio from './components/Portfolio.svelte';
</script>

<Header />

<main>
	<!-- <h1><span class='ambitious'>ambitious</span><span class='Nerds'>Nerds</span></h1> -->
  <p>We build software applications and web sites. Below is a small portfolio of our work.</p>
</main>

<Portfolio />

<Footer />

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		/* color: #FF6347; */
		font-size: 4em;
		font-weight: 100;
	}

  .ambitious {
    font-family: 'Kanit', sans-serif;
    font-size: 1em;
    font-weight: 600;
  }

  .Nerds {
    font-family: 'Orbitron', sans-serif;
    font-size: .8em;
    font-weight: 400;
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