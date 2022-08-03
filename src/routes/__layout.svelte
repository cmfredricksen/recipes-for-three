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
    }
</style>