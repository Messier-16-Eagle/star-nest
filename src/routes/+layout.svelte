<script>
	import '../app.pcss';
	import NavigationBar from '$lib/components/navigation-bar/navigation-bar.svelte';
	import Footer from '$lib/components/footer/footer.svelte';
</script>

<NavigationBar />
<slot />
<Footer />
