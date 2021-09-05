<script>
	import Card from '../components/Card.svelte'
</script>

<h1>
	About
</h1>
<Card>
	<h1 slot="title">Blog Post Title</h1>
	<!-- No slot named "description" was provided so the optional slot will not be rendered. -->
</Card>