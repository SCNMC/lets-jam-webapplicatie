<script>
	export let detailSpeaker;
	export let detailTitle;
	export let detailShortdescription;
	export let detailImage;
	import * as prismicH from "@prismicio/helpers";
</script>

<article>
	<img src={prismicH.asImageSrc(detailImage)} alt="#" />
	<div>
		<p>{@html prismicH.asHTML(detailSpeaker)}</p>
		<h1>{@html prismicH.asHTML(detailTitle)}</h1>
		<p>{@html prismicH.asHTML(detailShortdescription)} </p>
		<a href="/aanmelden">Aanmelden</a>
	</div>
</article>

<style>
	article {
		display: flex;
		flex-direction: column;
		gap: 2.5em;
		color: white;
		padding: 1em 3em;
	}

	img {
	}
	div {
		display: flex;
		flex-direction: column;
		gap: 2em;
	}

	@media (min-width: 70rem) {
		h1 {
			color: white;
			font-size: 2em;
		}

		article {
			display: flex;
			justify-content: center;
			align-items: flex-start;
			flex-direction: column;
			gap: 5em;
			padding: 0.1em 5em;

			/* padding: 5em; */
		}
		p {
			color: white;
		}
		a {
			text-align: center;
			background-color: #a675f5;
			color: #050542;
			width: 7em;
			padding: 0.5em;
			border-radius: 1em;
		}

		div {
			display: flex;
			flex-direction: column;
			justify-content: center;
			gap: 2em;
		}

		div :nth-child(3) {
			font-size: 1.5em;
		}
		img {
			max-width: 100%;
			height: 30em;
		}
	}
	@media (min-width: 90rem) {
		article {
			flex-direction: row;
			align-items: center;
		}
	}
</style>
