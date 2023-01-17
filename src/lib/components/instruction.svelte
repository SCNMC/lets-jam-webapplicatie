<script>
    import InstructionLink from "$lib/components/InstructionLink.svelte";
</script>

<!-- <section > -->
<section>
    <InstructionLink number="01"  instructionTitle= "kijk & orienteer" instructionDescription="Neem een kijkje naar de next events 
    en de upcoming events om jezelf te orienteren"/>
    <InstructionLink number="02"  instructionTitle= "Kies & orienteer" instructionDescription="Neem een kijkje naar de next events en de upcoming events om jezelf te orienteren"/>
    <InstructionLink number="03"  instructionTitle= "kies & orienteer" instructionDescription="Neem een kijkje naar de next events en de upcoming events om jezelf te orienteren"/>
</section>
  
<!-- </section> -->

<style>
     section {
        display: flex;
        flex-direction: column;
        justify-content: start;
      justify-content: start;
        padding: 1em;
        gap: 5em;
    }
   

    p{
        /* font-size: 1.5em; */
        color: #66e5bf;
    }
    h2{
        font-size: 2em;
        color: #66e5bf;
    }

    @media(min-width:60rem){
        section{
            flex-direction: row;
            align-items: center;
            justify-content: center;

        }
    }
</style>