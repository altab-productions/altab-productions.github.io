<script>
    import { base } from "$app/paths";
</script>

<div class="header--container">
    <a href="{base}/">Home</a>
    <a href="{base}/services">Services</a>
    <a href="{base}/contact">Contact</a>
</div>

<style>
    .header--container {
        display: flex;
        flex-direction: row;
        align-items: center;

        background-color: var(--turquoise--background);
        height: fit-content;
    }

    a {
        margin: 1rem;
        margin-right: 3rem;
        text-align: center;
        vertical-align: middle;

        font-family: Inter;
        font-style: normal;
        font-size: 2rem;
        font-weight: 400;

        color: white;
    }
</style>