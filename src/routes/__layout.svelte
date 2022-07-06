<script>
    import Nav from "../components/Navbar.svelte"
</script>

<Nav />

<slot><!-- optional fallback --></slot>

<style>
    :global(*) {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
</style>