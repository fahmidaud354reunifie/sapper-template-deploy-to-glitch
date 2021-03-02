<script type="text/javascript">
	// export let title, caption
	export let object
	console.log(object)
</script>


<!-- <h1>{title}</h1>

<p>{caption}</p> -->

{#if object}
{#each object as o}
<h1>{o.title}</h1>

<p>{o.caption}</p>
{/each}
{/if}