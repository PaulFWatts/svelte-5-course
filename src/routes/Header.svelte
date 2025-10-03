<script lang="ts">
    let {
        name,
        fake_name = 'Bob'   // default value if not provided
    }: {
        name: string;
        fake_name?: string; // optional prop

    } = $props();

</script>

<h1>Hello {name}</h1>
<h2>{name.replaceAll('u','o')}</h2>
{fake_name}

<style>

</style>