<script>
	// @ts-ignore
	export let data;
	// @ts-ignore
	const { title, date, Content } = data;
</script>

<article>
	<h1>{title}</h1>
	<p>Published: {date}</p>
	<Content />
</article>
