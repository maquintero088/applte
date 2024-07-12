<script context="module">
	// export const prerender = true;
</script>

<script>
	import Counter from '$lib/Counter.svelte';
</script>

<section>
	<div class="welcome">
		<picture>
			<!--<source srcset="svelte-welcome.webp" type="image/webp" />-->
			<img src="favicon.svg" alt="Márcel Quintero" />
		</picture>
	</div>
	<h1>
		Márcel Armando Quintero Carrillo
	</h1>
	<h2>
		Fullstack Developer & Software Engineer
	</h2>

	<!--<Counter />-->
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
	}

	h1 {
		color: #edf0f8;
		text-shadow: 1px 1px 6px #0006;
		width: 100%;
	}
	h2{
		color: white;
		font-size: x-large;
		font-weight: bold;
		margin-top: 0;
	}

	.welcome {
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
		margin-top: 2em;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
