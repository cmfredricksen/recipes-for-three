<script>
    import Nav from "$lib/nav.svelte";
</script>

<header>
    <h1>Dinner for Three</h1>
    <Nav />
</header>

<style>
    header {
        display: flex;
        justify-content: space-around;
        align-items: center;
        padding: 1rem;
        background-color: var(--clr-red);
    }
    
    h1 {
        color: var(--clr-purple);
        
    }
</style>