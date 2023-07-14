<script>
    import "../app.css";
    import { onMount } from 'svelte';

    let title = 'Checklist';
        onMount(() => {
        document.title = title; // Set the document title on component mount
    });
</script>

<slot />