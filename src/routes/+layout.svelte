<script>
	import Header from '$lib/components/layout/Header.svelte';
	import Footer from '$lib/components/layout/Footer.svelte';
</script>

<main>
	<Header />
	<slot />
	<Footer />
</main>
