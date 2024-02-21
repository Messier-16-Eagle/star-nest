<script>
	import FeaturedStory from '$lib/components/featured-story/featured-story.svelte';
	import EagleNebulaExploration from '$lib/assets/eagle-nebula-exploration.webp';
	import Astronaut from '$lib/assets/astronaut.svg';
</script>

<section class="flex justify-center p-4">
	<FeaturedStory
		image={EagleNebulaExploration}
		title="Illuminating the Cosmos: The Tech Behind 'Star Nest'"
		subtitle="Exploring the Svelte Framework's Role in Crafting an Interactive Journey Through the Eagle Nebula"
		author="Jinwoong Joung & Juseung Park"
		avatar={Astronaut}
		date="Feb 20, 2024"
		readingTime="5 min"
		href="/blog/illuminating-the-cosmos"
	/>
</section>
