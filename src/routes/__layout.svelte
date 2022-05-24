<script>
    import "../tailwind.css" 
    import Nav from "../components/navigation.svelte"
    import Footer from "../components/footer.svelte"
</script>
<Nav />
<div class="from-primary to-secondary text-primary-content -mt-[4rem] grid place-items-center items-end bg-gradient-to-br pt-20">
    <div class=" max-w-6xl mx-auto">
        <div class="p-5 text-base-content glass xl:rounded-box  grid max-w-screen-xl gap-4 bg-opacity-60 xl:pb-0">

            <slot></slot>
        </div>
        <Footer />
    </div>
</div>
