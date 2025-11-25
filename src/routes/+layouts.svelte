<script lang="ts">
    import Navigation from "../components/Navigation.svelte";

    let { children } = $props();

    // static site generation settings
    export const prerender = true;
    export const trailingSlash = "always";
</script>

<Navigation />

{@render children()}
