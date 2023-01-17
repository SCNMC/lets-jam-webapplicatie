
<script>
    export let number;
    export let instructionTitle;
    export let instructionDescription;
</script>

<div>
    <h1>01</h1>
    <h2>{instructionTitle}</h2>
    <p>{instructionDescription}</p>
</div>

<style>
    h1{
        margin-top: -1em;
        background-color: #050542;
        color: white;
        font-size: 3em;
        padding: .5em;
transform: translateX(-29%);

    }
    span{
        background-color: #050542;
        font-size: 3em;

    }
  
    div{
        display: flex;
        flex-direction: column;
      justify-content: flex-start;
      align-items: flex-start;
      background-color: #66e5bf;
 color: #050542;
        border-radius: .5em;
        padding: 1em ;
    gap: 2em;
    }

    p ::after{
        content: "HART";
    }
    li :nth-child(1){
        background-color: #050542;
    }
    p{
        font-size: 1.5em;
        padding-bottom: 1em;
    }
    h2{
        font-size: 3.5em;

    }

    @media(min-width:60rem){
    
div{
    flex-direction: column;
    justify-content: center;

}
    }
</style>