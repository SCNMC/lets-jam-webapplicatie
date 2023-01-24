<script>
	import DetailSection from "$lib/components/Detailcomponents/detailSection.svelte";
	import DetailHeader from "$lib/components/Detailcomponents/detailHeader.svelte";
	import DetailHero from "$lib/components/Detailcomponents/detailHero.svelte";
	export let data;
	console.log(data);
	const { document } = data;
</script>

<DetailSection>
	<DetailHeader title="fdnd" />
	<DetailHero
		detailSpeaker={data.sessionspeaker}
		detailTitle={data.sessiontitle}
		detailShortdescription={data.short_description}
	/>
</DetailSection>

