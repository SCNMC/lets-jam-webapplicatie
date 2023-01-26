<section>
	<h1>Featured sessions</h1>
	<p
		>Ontdek we love web sessions die op locatie worden gegeven.<br /> Voor meer
		informatie klik je op de desbetreffende we love web sessie. <br />Voor een
		overzicht van alle sessies ga je naar de agenda pagina.</p
	>
	<article>
		<slot />
	</article>
</section>

<style>
	section {
		display: grid;
		align-items: center;
		padding: 3em 1em;
		gap: 3em;
	}
	article {
		display: flex;
		align-items: center;
		flex-direction: column;
		gap: 3em;
		align-items: flex-start;
	}
	h1 {
		font-size: 2em;
		color: #66e5bf;
		font-weight: bold;
	}
	h1::before {
		content: "♥";
		background-color: #66e5bf;
		color: #000000;
		font-size: 2rem;
		border-radius: 3rem;
		padding: 0.1em 0.3em;
		margin-right: 0.7em;
		animation: pulse-animation 2s infinite;
	}
	/* @keyframes pulse-animation {
		0% {
			box-shadow: 0 0 0 0px #020202;
		}
		100% {
			box-shadow: 0 0 0 12px #7859a8;
		}
	} */
	p {
		color: #a675f5;
		font-size: 1.5em;
	}
	@media (min-width: 50rem) {
		article {
			display: grid;
			align-items: center;
			grid-template-columns: 1fr 1fr;
		}
		img {
			width: 100%;
		}
		@media (min-width: 70rem) {
			section {
				padding: 6em 5em;
				gap: 4em;
			}
			article {
				display: grid;
				grid-template-columns: 1fr 1fr;
				gap: 5em;
			}
			p {
				font-size: 2em;
			}
		}
	}
</style>
