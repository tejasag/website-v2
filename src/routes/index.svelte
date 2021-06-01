<script lang="ts">
    import LandingPage from "$lib/LandingPage.svelte";
    import AboutPage from "$lib/AboutPage.svelte";
    import ContactPage from "../lib/ContactPage.svelte";
    import ProjectsPage from "../lib/ProjectsPage.svelte";
</script>

<svelte:head>
    <title>Tejas Agarwal</title>
</svelte:head>

<main>
    <LandingPage/>
    <AboutPage/>
    <div style="height: 100vh;"></div>
<!--    <ProjectsPage />-->
<!--    <ContactPage />-->
</main>
