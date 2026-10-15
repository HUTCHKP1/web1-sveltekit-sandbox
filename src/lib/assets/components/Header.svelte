<script>
    import Navigation from './Nav.svelte';
    let {title = 'Sveltekit components',
        subtitle = 'For more information see the svelteKit tutorial',
        navItems = []
    } = $props();
</script>
<header>
    <h1>{title}</h1>
    <p>{subtitle}</p>
    <Navigation items = {navItems} />
</header>

<!-- <article class="card">
<Picture />
<Details /> -->
<!-- 
</article> -->
<style>
    header{
        background-color: black;
    padding: 20px;
    text-align: center;
    border-bottom: 1px solid #ccc;
    }
</style>