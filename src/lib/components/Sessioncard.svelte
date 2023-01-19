<script>
	import * as prismicH from '@prismicio/helpers';



</script>
<section>
	<ul>
	
		<li>
      <p>Shauri</p>
			<img src="/images/weloveweb.jpeg" />
			<div>
				<p>GREENSOCK</p>
				<p>SEE MORE</p>
			</div>
		</li>
    <!-- <li>
      <p>SHAURI MAIGUA</p>
			<img src="/images/weloveweb.jpeg" />
			<div>
				<p>RESPONSIVE DESIGN</p>
				<p>SEE MORE</p>
			</div>
		</li>
    <li>
      <p>SHAURI MAIGUA</p>
			<img src="/images/weloveweb.jpeg" />
			<div>
				<p>CREATIVE CODING</p>
				<p>SEE MORE</p>
			</div>
		</li>
    <li>
      <p>SHAURI MAIGUA</p>
			<img src="/images/weloveweb.jpeg" />
			<div>
				<p>CREATIVE CODING</p>
				<p>SEE MORE</p>
			</div>
		</li>
	</ul> -->
</section>

<style>
	section ul {
display:flex;
justify-content: center;
align-items: center;
flex-direction: column;
    gap: 3em;
		width: 100%;
	}

  div{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
padding-top: .5em;
  }
  div :nth-child(1){
    font-weight: bold;
    font-size: 1em;
  }
	a {
		color: #a675f5;
	}

	li {
		color: #a675f5;
	}

	img {
    width: 100%;
object-fit: cover;
    padding-top: .5em;
	}

  @media(min-width:40rem){
section ul{
display: grid;
grid-template-columns: 1fr 1fr;

}
@media(min-width:60rem){
section ul{
display: grid;
grid-template-columns: 1fr 1fr;
gap: 5em;
}
 img{
  height: 30em;
 }
}
  }
</style>
