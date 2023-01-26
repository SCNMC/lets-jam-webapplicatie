<script>
	import Mainhero from "$lib/components/Mainhero.svelte";
	import Header from "$lib/components/header.svelte";
	import Loader from "$lib/components/loader.svelte";
	import Introduction from "$lib/components/Introduction.svelte";
	import SessionSection from "$lib/components/SessionSection.svelte";
	import Sessioncard from "$lib/components/Sessioncard.svelte";
	import SeeMore from "$lib/components/seeMore.svelte";
	import PageTransition from "$lib/components/PageTransition.svelte";
	import { onMount } from "svelte";
	import { gsap } from "gsap/dist/gsap";
	import * as prismicH from "@prismicio/helpers";
	export let data;
	const { document } = data;
	console.log(document);
</script>

<Loader />
<PageTransition>
<Header title="fdnd" />
<Mainhero />
<Introduction />
<SessionSection>
	{#each data.document as data}
		<Sessioncard
			sessionspeaker={data.data.sessionspeaker}
			sessiontitle={data.data.sessiontitle}
			sessionImg={data.data.image}
			dataUid={data.uid}
		/>
	{/each}
</SessionSection>
<SeeMore />
</PageTransition>

