<script>
	import "./layout.css";
	import "aos/dist/aos.css";
	import favicon from "$lib/assets/favicon.svg";
	import AOS from "aos";
	import { onMount } from "svelte";

	let { children } = $props();

	onMount(() => {
		AOS.init({
			once: true,
			disable: "phone",
			duration: 700,
			easing: "ease-out-cubic",
		});
	});
</script>

<svelte:head>
	<title>Svelte kit landing page</title>
	<meta name="description" content="Svelte kit landing page" />
	<link rel="icon" href={favicon} />
</svelte:head>

<div
	class="flex min-h-screen flex-col overflow-hidden supports-[overflow:clip]:overflow-clip"
>
	{@render children()}
</div>
