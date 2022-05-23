<script>
    import "../tailwind.css" 
    import Nav from "../components/navigation.svelte"
    import Footer from "../components/footer.svelte"
</script>
<div class=" max-w-6xl mx-auto">
    <Nav />
    <slot></slot>
    <Footer />
</div>
