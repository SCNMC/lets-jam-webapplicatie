<script>
export let detailSpeaker
export let detailTitle;
export let detailShortdescription
import * as prismicH from "@prismicio/helpers";
</script>
<article>
    <img src="/images/weloveweb.jpeg" alt="weloveweb">
    <div>
        <p>{@html prismicH.asHTML(detailSpeaker)}</p>
        <h1>{@html prismicH.asHTML(detailTitle)}</h1>
        <p>{@html prismicH.asHTML(detailShortdescription)} </p>
        <a href="">Aanmelden</a>
    </div>
</article>

<style>
    article{
        display: flex;
flex-direction: column;
gap: 2.5em;
        color: white;
        padding: 1em 3em;

        
    }

    img{
        max-width: 100%;
    }
    div{
        display: flex;
        flex-direction: column;
        gap: 2em;

    }

    

@media(min-width:70rem){
h1{
    color: white;
    font-size: 2.5em;
}

article {
    display: flex;
    justify-content: center;
    align-items: center;
flex-direction: row;
gap: 4em;
/* padding: 5em; */
}
p{
    color: white;
}
a{
    text-align: center;
    background-color: #a675f5;
    color: #050542;
    width: 7em;
    padding: .5em;
    border-radius: 1em;
}

div{
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 1.5em;
}

div :nth-child(3){
    font-size: 1.5em;
}
img{
width: 100%;
} 
}
</style>
