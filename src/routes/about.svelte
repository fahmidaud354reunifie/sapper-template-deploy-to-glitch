<script type="text/javascript">
	import Card from '../components/Card.svelte'

	// const title = "About this site"
	// const caption = "This is the 'about' page. There's not much here."

	const object = [{
		title: "About this site",
		caption: "This is the 'about' page. There's not much here.",
	}]
</script>

<svelte:head>
	<title>About</title>
</svelte:head>

<!-- <Card title={title} caption={caption} /> -->
<!-- {#if object} -->
<Card object={object} />
<!-- {/if} -->
