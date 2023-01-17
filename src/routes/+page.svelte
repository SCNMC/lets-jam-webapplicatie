<script>
	import Mainhero from "$lib/components/Mainhero.svelte";
	import Header from "$lib/components/header.svelte";
	import Loader from "$lib/components/loader.svelte";
	import Introduction from "$lib/components/Introduction.svelte";
	import Sessions from "$lib/components/Sessions.svelte";
	import Sessioncard from "$lib/components/Sessioncard.svelte";
	import Interesse from "$lib/components/Interesse.svelte";
	import Instruction from "$lib/components/instruction.svelte";
	import Weloveweb from "$lib/components/weloveweb.svelte";
	import { onMount } from "svelte";
	import { gsap } from "gsap/dist/gsap";
</script>

<Loader />
<Header title="fdnd"
/>
<Mainhero/>
<Introduction />
<Sessions>
<Sessioncard/>
</Sessions>

