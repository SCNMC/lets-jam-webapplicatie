<section>
    <h1> Featured sessions.</h1>
    <p>Ontdek interresante we ♥ web sessions. Wij hebben een ruime variatie van onderwerpen dus er is voor iedereen iets interresants.</p>
    <slot/>
</section>

<style>
    section{
        display: flex;
justify-content: start;
flex-direction: column;
gap: 3em;
padding: 3em 1em;
align-items: flex-start;
    height: 100vh;
    }
    h1{
        font-size: 2em;
        color: #66e5bf;
        font-weight: bold;
    }
    h1::before{
        content: "♥";
        background-color: #66e5bf;
color: #000000;
        font-size: 2rem;
		border-radius:3rem;
        padding: .1em .3em;
        margin-right: .7em;
        animation: pulse-animation 2s infinite;
    }
    @keyframes pulse-animation {
  0% {
    box-shadow: 0 0 0 0px #020202;
  }
  100% {
    box-shadow: 0 0 0 12px #7859a8;
  }
}
    p{
        color: #a675f5;
        font-size: 1.5em;
    }


</style>