<script>
import * as prismicH from '@prismicio/helpers';
export let sessionspeaker;
export let sessiontitle
export let sessionImg;

</script>
<!-- <section> -->
	<ul>
		<a href="#">
		<li>
      <p>{@html prismicH.asText(sessiontitle)}</p>
			<img src={prismicH.asImageSrc(sessionImg)} />
			<div>
				<p>{@html prismicH.asHTML(sessionspeaker)}</p>
				<p>Info</p>
			</div>
		</li>
	</a>
		</ul>
<!-- </section> -->

<style>
	/* section ul {
display:flex;
justify-content: center;
align-items: center;
flex-direction: column;
    gap: 10em;
		width: 100%;
	} */

  div{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
padding-top: .5em;
  }
  div :nth-child(1){
    font-size: 1em;
  }
	a {
		color: #a675f5;
	}

	li {
		color: #a675f5;
	}

	li> p{
		text-align: center;
		border-radius: 1em;
		padding: .2em ;
		width: 100%;
		color: #050542;
		background-color: #a675f5;
	}
	div > :nth-child(2){
	text-align: center;
		border-radius: .7em;

		width: 4em;
		color: #050542;
background-color: #66e5bf;
}
div  :nth-child(1){
	text-align: center;
	background-color: #a675f5;
	color: #050542;
	border-radius: .7em;
width: 8em;
}

	img {
    width: 100%;
object-fit: cover;
    padding-top: 1em;
	}

  @media(min-width:40rem){
section ul{
/* display: grid;
grid-template-columns: 1fr 1fr ; */
}

@media(min-width:70rem){

section ul {
/* display: grid;
grid-template-columns: 1fr 1fr ; */
/* gap: 5em; */
}
li > p{
		text-align: center;
		border-radius: 1em;
		padding: .1em ;
		width: 50%;
		color: #050542;
		background-color: #a675f5;
	}
 img{
  height: 25em;
 }
}
  }
</style>
