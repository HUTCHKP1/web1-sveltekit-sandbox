<script>
    let title = $state("Home");
    import Card from "$lib/assets/components/Card.svelte";
</script>

<h1>{title} - Portfolio</h1>
<p>Welcome to my home page!</p>
<!-- <nav>
    <a href="/">Home</a>
    <a href="/about">About</a>
    <a href="/content">Content</a>
    <a href="/gallery">Gallery</a>
</nav> -->
<main>
    <Card />
    <Card />
    <Card />
</main>

<style>
    main{
        display: flex;
        flex-wrap: wrap;

    }
</style>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>
