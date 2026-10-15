<svelte:head>
    <title>SvelteKit Components  Demo</title>
    <meta name="description" content = "A demonstration of reusable SvelteKit components and props." />
</svelte:head>
<Header
    title = "Welcome to Web Development"
    subtitle = "Learning reusable components and props"
   
/>
<main>
    <h2>Our Example Card</h2>

    <Card
        title = "Learning SvelteKit"
        description = "Components let us reuse interface elements across our application"
    />
    <Card
        title = "Understanding Props"
        description = "Props allow us to customise each component with different data"
    />
</main>

