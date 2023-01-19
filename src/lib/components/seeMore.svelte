<section>
    <p>Interesse?<br>Kijk dan op onze agenda</p>
    <div>
        <p>	&rarr;</p>
    <a href> Ga naar de pagina</a>
</div>
</section>

<style>
    section{
        display: flex;
        flex-direction: column;
align-items:center;
justify-content: center;
        padding: .1em 1em;
        gap: 3em;
        min-height: 40vh;
        background-color: #a675f5;
    }
    div{
        display: flex;
        flex-direction: row ;
      align-items: center;
      justify-content: start;
      gap: 1em;
    }

    div > p{
        text-align: center;
        border: 2px solid #050542;
		border-radius: 3rem;
		padding: .2em;
        width: 1.5em;
    }
    p{
        font-size: 2em;
    }
    a{
        font-weight: bold;
    }


		@media (min-width: 60rem) {
		section{
            padding:.5em  5em;
            flex-direction: row;
            align-items: center;
            justify-content: space-between;
        }
        div{
align-items: center;
        }
       section >  p{
            font-size: 3em;
        }
        a{
            font-size: 1.5em;
        }
		}
</style>