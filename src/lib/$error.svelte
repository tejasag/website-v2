<script context="module">
    export function load({ error, status }) {
        return {
            props : {
                title: `${status} ${error.message}`
            }
        }
    }
</script>

<script lang="ts">
    export let title: string;
</script>

<h1>{title}</h1>