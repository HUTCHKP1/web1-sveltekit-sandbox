<script>
	import '../styles/global.css'; //importing global styles
	import favicon from '$lib/assets/favicon.svg';
	import Header from '$lib/assets/components/Header.svelte';
	import Footer from '$lib/assets/components/Footer.svelte';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>
<Header />

{@render children()}

<Footer />
