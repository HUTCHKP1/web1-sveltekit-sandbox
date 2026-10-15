<script>
    let {items = [] } = $props();
</script>
<nav aria-label="Main navigation">

    <ul>
        {#each items as item}
        <!-- <li> -->
            <a href={item.href}>{item.label}</a>
        <!-- </li> -->
        {/each}
        </ul>
</nav>

<style>
    nav{
    background-color:black;
    padding: 20px;
    text-align: center;
    }
    nav a{
        margin: 0 15px;
        text-decoration: none;
        color: chocolate;
        font-weight: bold;
    }
    nav a:hover{
        text-decoration: underline;
    }
 </style>