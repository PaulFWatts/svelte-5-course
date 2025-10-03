<script lang="ts">
let {name}: {name: string} = $props();
</script>

<h1>Hello {name}</h1>
<h2>{name.replaceAll('u','o')}</h2>

<style>

</style>