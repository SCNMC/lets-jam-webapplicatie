<script>
    import Mainhero from "$lib/components/Mainhero.svelte";
    import Header from "$lib/components/header.svelte";
    import Loader from "$lib/components/loader.svelte";
    import Introduction from "$lib/components/Introduction.svelte";
    import Weloveweb from "$lib/components/weloveweb.svelte";
    import { onMount } from "svelte";
	import { gsap } from "gsap/dist/gsap";

</script>

<Loader/>
<Header/>
<Mainhero>
    <Weloveweb/>
</Mainhero>
<Introduction/>

