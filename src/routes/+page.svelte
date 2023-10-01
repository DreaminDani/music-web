<script>
	import Band from '$lib/Band.svelte';
</script>

<h1>My Music</h1>
<div class="container">
	<Band
		img="puppy.jpg"
		name="Puppy on Parade"
		years="2023–Present"
		link="https://open.spotify.com/artist/4uTDRgVhgPJx7jv3s7ZEGM"
	/>
	<Band
		img="life.jpg"
		name="Life After Parties"
		years="2019–2021"
		link="https://youtu.be/NCk3BX-rPoM"
	/>
	<Band
		img="local.jpg"
		name="Local Point"
		years="2015–2016"
		link="https://localpoint.bandcamp.com/"
	/>
	<Band
		img="daniel.jpg"
		name="Daniel Sandoval"
		years="2014–2022"
		link="https://open.spotify.com/artist/47mXmNmm2ekoxyCwowItaX?si=fVM4Puc9TFmu1Bcxb5C7hg"
	/>
</div>

<style>
	:global(body) {
		margin: 52px;
	}
	h1 {
		color: #326990;
		font-family: Raleway;
		font-size: 60px;
		font-style: normal;
		font-weight: 700;
		line-height: normal;
		letter-spacing: -0.3px;
	}
	.container {
		display: flex;
		width: 100%;
		gap: 24px;
	}
	@media (max-width: 800px) {
		:global(body) {
			margin: 24px;
		}
		.container {
			flex-direction: column;
		}
		h1 {
			font-size: 40px;
		}
	}
</style>
