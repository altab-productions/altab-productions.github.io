<script>
    import Header from "$lib/components/Header.svelte";
    import Footer from "$lib/components/Footer.svelte";
    import "$lib/styles/reset.css";
    import "$lib/styles/colors.css";
    import "$lib/styles/fonts.css";
    import "$lib/styles/defaults.css";
</script>
<body>
    <Header/>
    <main>
        <slot/>
    </main>
    <Footer/>
</body>

<style>
    * {
        font-family: 'Freigeist',Arial,sans-serif;
    }

    body {
        display: flex;
        flex-direction: column;

        min-height: 100vh;
        margin: 0;
    }

    main {
        flex: 1;
    }

</style>