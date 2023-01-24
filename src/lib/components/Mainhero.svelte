<script>
	import { onMount } from "svelte";
	import { gsap } from "gsap/dist/gsap";
	onMount(() => {
        gsap.from(
        "header, .weloveweb ",
        2,
        {
          y: "200",
          opacity: 0,
          ease: "Expo.easeInOut",
          delay: 2.5,
          stagger: 0.08,
		});
	});
	
</script>

<section class="container">
<section>
	<img src="/images/weloveweb.jpeg" alt="fdnd" />
	<h2>FRONTEND DESIGN<br /><span class="space">& </span><span>DEVELOPMENT.</span></h2>
    <slot/>
</section>

<div class="weloveweb">
	<p>WE</p><span>♥</span><p>THE</p>
	<p> WEB </p>
</div>
</section>

<style>
    .container{
       min-height: 80vh;
        padding: 3em 1em;
        }

        section{
            display: flex;
            flex-direction: column;
            gap: 3em;
        }
    
	/* section {
		display: flex;
		flex-direction: column;
		color: white;
		padding: 3em 1em;
		gap: 2em;
		line-height: 3.5em;
        min-height: 100vh;
	} */
	/* h2{
        font-size: 2.5em;
        font-weight: bold;
    } */
	img {
	height: 100%;
        border-radius: .5em;
	}
	h2 {
		width: fit-content;
		font-size: 2em;
        color: white;
		background-color: #050542;
		border-top-right-radius: 15px;
		margin-top: -3em;
		padding-right: 0.2em;
        line-height: 2em;
	}
    .space{
padding-right: 1em;
    }


	div {
		display: flex;
		align-items: center;
		gap: 1em;
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
			height: 100%;
		}
	}
    @media (min-width: 45rem) {
		.container{
            padding: .1em 5em;
			min-height: 90vh;
        }
        /* section{
            padding: 1em 1em;
        } */
		img {
			height: 100%;
		}
        h2{
            font-size:4em;
            line-height: 1.5em;
        }
        p {
			font-size: 2.5em;
		}
        div {
			justify-content: start;
			gap: 2em;
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
	}

	@media (min-width: 60rem) {
        .container{
            padding: .1em 5em;
			min-height: 90vh;
        }
		p {
			font-size: 2.5em;
		}
		img {
			max-height:35rem;
			object-fit: cover;
		}
		/* section {
			padding: 2em 4em;
		} */
		div {
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
			font-size: 5.5em;
			margin-top: -3em;
			line-height: 1.3em;
		}
	}
</style>
