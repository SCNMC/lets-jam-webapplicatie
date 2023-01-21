<script>
    import DetailHeader from "./detailHeader.svelte";
</script>

<section>
    <slot/>
</section>

<style>
    section{
display: flex;
flex-direction: column;
justify-content: center;
min-height: 100vh;
    background: -webkit-linear-gradient(70deg, #a675f5 40%, #050542 10%);
  background: -o-linear-gradient(50deg, #a675f5 40%, #050542 4%);
  background: -moz-linear-gradient(90deg,#a675f5 40%, #050542 4%);
  background: linear-gradient(90deg, #a675f5 27%, #050542 4%);

    
    }
</style>