<section>
	<p>WE LOVE WEB SESSIES ZIJN</p>
	<p>SESSIES WAAR GASTSPREKERS</p>
	<p>UIT DE FRONT END WERELD</p>
	<p>OVER HUN BEROEP EN</p>
	<p>ERAVERINGEN KOMEN </p>
	<p>VERTELLEN.</p>
	<a href="">&#8595;</a>
</section>

<style>
	section {
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
		min-height: 100vh;
		background-color: #a675f5;
		color: white;
	}
	section :nth-child(2) {
		text-indent: -2em;
	}
	section :nth-child(3) {
		text-indent: 2.5em;
	}
	section :nth-child(4) {
		text-indent: -5em;
	}
	section :nth-child(5) {
		text-indent: 5em;
	}
	section :nth-child(6) {
		text-indent: -5em;
		padding-bottom: 2em;
	}

	p {
		text-align: start;
		display: inline-block;
		color: #050542;
		font-size: 1.4em;
		padding: 0.2em;
		font-weight: bolder;
	}
	a {
		text-align: center;
		color: #050542;
		border: 2px solid #050542;
		border-radius: 5rem;
		font-size: 2em;
		padding: 0.5rem;
		border-radius: 7rem;
		width: 1.5em;
	}
	@media (min-width: 40rem) {
		p {
			font-size: 3em;
		}
	}
	@media (min-width: 60rem) {
		p {
			font-size: 3.5em;
		}
		a {
			font-size: 3em;
		}
		section :nth-child(6) {
			text-indent: -5em;
			padding-bottom: 1.5em;
		}
	}
</style>
