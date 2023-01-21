<script>
import DetailSection from "$lib/components/Detailcomponents/detailSection.svelte";
import DetailHeader from "$lib/components/Detailcomponents/detailHeader.svelte";
import DetailHero from "$lib/components/Detailcomponents/detailHero.svelte";
export let data;
</script>

<DetailSection>


<DetailHeader title="fdnd"
/>
<DetailHero
detailSpeaker={data.sessionspeaker}

/>
</DetailSection>
<!-- <h2>{@html prismicH.asHTML(data.data.sessionspeaker)}</h2> -->
<main>


    


</main>