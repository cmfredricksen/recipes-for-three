<script>
    const links = [
        {
            title: "Home",
            path: "/"
        },
        {
            title: "Recipes",
            path: "/recipes"

        },
        {
            title: "Articles",
            path: "/articles"
        }
    ]
</script>

<nav>
    {#each links as {title, path} }
        <a href={path}>{title}</a>
    {/each}
</nav>

<style>

    a {
        color: var(--clr-blue-lt);
        margin: 0 1rem;
    }
</style>

