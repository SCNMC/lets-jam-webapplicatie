<script>
	import * as prismicH from "@prismicio/helpers";
	export let sessionspeaker;
	export let sessiontitle;
	export let sessionImg;
	export let dataUid;
</script>

<ul>
	<a href={dataUid}>
		<li>
			<p>{@html prismicH.asHTML(sessiontitle)}</p>
			<img src={prismicH.asImageSrc(sessionImg)} alt="#" />
			<div>
				<p>{@html prismicH.asHTML(sessionspeaker)}</p>
				<p>Info</p>
			</div>
		</li>
	</a>
</ul>

<style>
	div {
		display: flex;
		flex-direction: row;
		justify-content: space-between;
		padding-top: 0.5em;
	}
	div :nth-child(1) {
		font-size: 1em;
	}
	a {
		color: #a675f5;
	}

	li {
		color: #a675f5;
	}

	li > p {
		text-align: center;
		border-radius: 1.5em;
		padding: 0.5em;
		font-size: 0.7em;
		color: white;
		border: 3px solid white;
		/* background-color: #a675f5; */
	}
	div > :nth-child(2) {
		text-align: center;
		border-radius: 0.7em;
		width: 8em;
		color: #050542;
		background-color: #66e5bf;
		padding: 0.2em;
	}
	div :nth-child(1) {
		text-align: center;
		background-color: #a675f5;
		color: #050542;
		border-radius: 0.7em;
		width: 8em;
		padding: 0.2em;
	}

	img {
		width: 100%;
		object-fit: cover;
		padding-top: 1em;
	}

	@media (min-width: 40rem) {
		section ul {
			/* display: grid;
grid-template-columns: 1fr 1fr ; */
		}

		@media (min-width: 70rem) {
			section ul {
				/* display: grid;
grid-template-columns: 1fr 1fr ; */
				/* gap: 5em; */
			}
			li > p {
				font-size: 0.9em;
				text-align: center;
				border-radius: 1em;
				padding: 0.1em;
				width: 100%;
			}
			img {
				height: 25em;
			}
		}
	}
</style>
