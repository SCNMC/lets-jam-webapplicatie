<script>
	import DetailSection from "$lib/components/Detailcomponents/detailSection.svelte";
	import DetailHeader from "$lib/components/Detailcomponents/detailHeader.svelte";
	import DetailHero from "$lib/components/Detailcomponents/detailHero.svelte";
	import DetailIntroduction from "$lib/components/Detailcomponents/detailIntroduction.svelte";
	import PageTransition from "$lib/components/PageTransition.svelte";
	export let data;
	console.log(data);
	const { document } = data;
</script>

<PageTransition>
	<DetailSection>
		<DetailHeader title="fdnd" />
		<DetailHero
			detailSpeaker={data.sessionspeaker}
			detailTitle={data.sessiontitle}
			detailShortdescription={data.description}
			detailImage={data.image}
		/>
		<DetailIntroduction />
	</DetailSection>
</PageTransition>




