<script lang="ts">
    import Counter from "$lib/Counter.svelte";
    import image from "$assets/figma.png";
</script>

<main>
    <img src={image} alt="figma logo" height="80" />
    <h1 class="figma-font-ui14-bold">Svelte + Figma = 🔥</h1>
    <Counter class="align-self" />
</main>

<style>
    main {
        display: grid;
        justify-items: center;
        height: 100%;
        padding: var(--figma-size-large);
    }
    h1 {
        text-align: center;
    }
</style>
