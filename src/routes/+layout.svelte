<script>
	import './styles.css';
</script>

<div class="app">

	<main>
		<!-- TODO Header (Nav bar) -->
		<slot />
	</main>

	<footer>
		<p>Made with <span class="heart">&#9829;</span> by <a href="https://dzge.de/">Daniel Gebhardt</a></p>
	</footer>
</div>

<style>
	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 12px;
	}

	footer a {
		font-weight: bold;
	}

	footer .heart {
		color: red;
	}

	@media (min-width: 480px) {
		footer {
			padding: 12px 0;
		}
	}
</style>
