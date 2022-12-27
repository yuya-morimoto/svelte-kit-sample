<script lang="ts">
	export let data: { title: string; content: string };
</script>

<h1>{data.title}</h1>
<div>{@html data.content}</div>
