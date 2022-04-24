



<script>
    import Title from '$lib/title.svelte'
    import '../global.css'
</script>

<header>
    <Title title = "Ninja Gaming"/>
</header>

<main>
<slot></slot>
</main>

<footer>
    <p>Copyright 2022 toftof</p>
</footer>

<style>
    header {
        display: flex;
        justify-content: center;
    }
    main {
        max-width: 960px;
        margin: 20px auto;
    }
    footer {
        text-align: center;
    }
</style>