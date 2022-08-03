<script>
    import "../global.css"
    import Header from "$lib/header.svelte";
    import Footer from "$lib/footer.svelte";
</script>

<Header />
<div class="wrapper">
    <slot></slot>
</div>
<Footer />

<style>
    .wrapper {
        display: flex;
        flex-direction: column;
        width: 80%;
        margin-left: 10%;
        margin-right: 10%;
        border: 2px solid yellow;
        background-color: var(--clr-purple)
    }
</style>