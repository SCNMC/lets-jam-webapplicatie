<script>
        import { onMount } from "svelte";
	import { gsap } from "gsap/dist/gsap";
    onMount(() => {
		gsap.to(".background", 5, {
			y: "-100%",
			ease: "Expo.easeInOut",
			delay: 0,
		});
        gsap.to(".green", 2, {
			y: "-100%",
			ease: "Expo.easeInOut",
			delay: 0,
		});
        gsap.to(".blue", .5, {
			y: "-100%",
			ease: "Expo.easeInOut",
			delay: 0,
		});
	});
</script>

<div class="background" />
<div class="green"></div>
<div class="blue"></div>

<style>	
.background {
    background-color:#a675f5;
    opacity: 1;
    position: absolute;
    top: 0;
    bottom: 0;
    right: 0;
    left: 0;
    z-index: 2;
    
}

.green{
    background-color: #66e5bf;
    opacity: 1;
    position: absolute;
    top: 0;
    bottom: 0;
    right: 0;
    left: 0;
    z-index: 3;

}
.blue{
    background-color: #050542;
    opacity: 1;
    position: absolute;
    top: 0;
    bottom: 0;
    right: 0;
    left: 0;
    z-index: 4;

}
</style>