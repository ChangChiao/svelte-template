<script>
	import "../app.css";
	let name = 'world';
</script>

<nav>
	<a href="/">home</a>
	<a href="/about">about</a>
</nav>

<slot />


<style lang="postcss">
	:global(html) {
	  background-color: theme(colors.gray.100);
	}
  </style>
