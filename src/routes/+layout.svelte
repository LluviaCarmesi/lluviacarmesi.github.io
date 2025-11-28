<script lang="ts">
    import Navigation from "../components/Navigation.svelte";

    let { children } = $props();
</script>

<Navigation />

{@render children()}
