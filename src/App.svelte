<script lang="ts">
	import Footer from './components/Footer.svelte'
	export let appName: string;
</script>

<main id="app-wrapper">
	<h2>Welcome to</h2>
	<h1>{appName}</h1>
	<Footer appName={appName} />
</main>

<style lang="scss">
	#app-wrapper {
		height: 100vh;
		width: 100vw;
		max-height: 100%;
		max-width: 100%;
		overflow: hidden;
		padding: 0;
		margin: 0;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		line-height: 3rem;
		font-size: 3em;
		font-weight: 100;
	}

	h2 {
		color: #666666;
		line-height: 1.5rem;
		padding: 0;
		margin: 0;
	}
	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>