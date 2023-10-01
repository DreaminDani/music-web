<script>
	/**
	 * @type {String}
	 */
	export let img;
	/**
	 * @type {String}
	 */
	export let name;
	/**
	 * @type {String}
	 */
	export let years;
	/**
	 * @type {String}
	 */
	export let link;
</script>

<a class="band" href={link}>
	<img src={img} alt={`Image representing ${name}`} />
	<h2>{name}<br />({years})</h2>
</a>

<style>
	a {
		display: block;
		text-decoration: none;
		color: #24292f;
	}

	a:hover {
		color: #77bf51;
	}

	h2 {
		text-align: center;
		font-family: Raleway;
		font-size: 32px;
		font-style: normal;
		font-weight: 500;
		line-height: normal;
	}

	img {
		width: 100%;
		border-radius: 4px;
		box-shadow: -4px 4px 4px 0px rgba(0, 0, 0, 0.12);
	}
</style>
