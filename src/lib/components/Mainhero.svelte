<section>
	<img src="/images/weloveweb.jpeg" alt="fdnd" />
	<h2>FRONTEND DESIGN<br />& <span>DEVELOPMENT</span></h2>
</section>

<div>
	<p>WE</p><span>♥</span><p>THE</p>
	<p> WEB </p>
</div>

<style>
	section {
		display: flex;
		flex-direction: column;
		color: white;
		padding: 3em 1em;
		gap: 2em;
		line-height: 3.5em;
	}
	/* h2{
        font-size: 2.5em;
        font-weight: bold;
    } */
	img {
		width: 100%;
	}
	h2 {
		width: fit-content;
		font-size: 2em;
		background-color: #050542;
		border-top-right-radius: 15px;
		margin-top: -3em;
		padding-right: 0.5em;
	}
	div {
		display: flex;
		align-items: center;
		gap: 2em;
		padding: 1em;
	}
	div :nth-child(1) {
		color: #050542;
		padding: 1em;
		background-color: #a675f5;
		font-weight: bold;
	}
	div :nth-child(2) {
		text-align: center;
		background-color: #66e5bf;
		font-size: 2.5rem;
		border-radius: 2rem;
		width: 4rem;
	}
	div :nth-child(3) {
		color: white;
		border: 2px solid white;
		border-radius: 2rem;
		padding: 1em;
	}
	div :nth-child(4) {
		background-color: #a675f5;
		padding: 1em;
		width: 5rem;
		border-radius: 2rem;
		text-align: center;
	}

	@media (min-width: 25rem) {
		img {
			height: 25em;
		}
	}

	@media (min-width: 60rem) {
		p {
			font-size: 2.5em;
		}
		img {
			height: 35rem;
			object-fit: cover;
		}
		section {
			padding: 2em 4em;
		}
		div {
			padding-left: 4em;
			justify-content: start;
			gap: 4em;
		}

		div :nth-child(1) {
			padding: 0.4em;
		}
		div :nth-child(2) {
			font-size: 4.5rem;
			border-radius: 4rem;
			width: 6.5rem;
		}
		div :nth-child(3) {
			padding: 1rem;
			border-radius: 7rem;
		}
		div :nth-child(4) {
			padding: 0.4em;
			width: 20rem;
			border-radius: 4em;
		}
		h2 {
			font-size: 5em;
			margin-top: -3em;
			line-height: 1.4em;
		}
	}
</style>
