<script lang="ts">
    import LandingPage from "$lib/LandingPage.svelte";
    import AboutPage from "$lib/AboutPage.svelte";
    import AOS from "aos";

    AOS.init();
</script>

<svelte:head>
    <title>Tejas Agarwal</title>
</svelte:head>

<main>
    <LandingPage />
    <AboutPage />
</main>
