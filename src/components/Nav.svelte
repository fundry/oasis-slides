<script>
	export let segment;
</script>

<style>
	nav {
		background: #6800ED;
		color : #fff ;
		display: flex;
		margin : 0rem;
		justify-content: space-between;
		font-weight: 300;
		padding: 0 2em;
	}

	ul {
		padding: 0;
	}

	/* clearfix */
	ul::after {
		content: '';
		display: block;
		clear: both;
	}

	li {
		display: block;
		float: left;
		margin : 0rem 1rem;
	}

	[aria-current] {
		position: relative;
		display: inline-block;
	}

	[aria-current]::after {
		position: absolute;
		content: '';
		width: calc(100% - 1em);
		height: 2px;
		background-color: rgb(255,62,0);
		display: block;
		bottom: -1px;
	}

	a {
		text-decoration: none;
		padding: 1em 0.5em;
		display: block;
	}

	h2 {
		display : flex;
		justify-content: center;
		align-items: center;
		font-weight: 500;
		font-size: 1.6rem;
	}

	h2:hover{
		cursor: pointer;
	}

</style>

<nav>
	<h2> Slides </h2>

	<ul>
		<li><a aria-current="{segment === undefined ? 'page' : undefined}" href=".">Slides</a></li>

		<li><a rel=prefetch aria-current="{segment === 'blog' ? 'page' : undefined}" href="blog">Editor</a></li>
	</ul>
</nav>
