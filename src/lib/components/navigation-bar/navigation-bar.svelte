<script>
	import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';
	import StarGraph from '$lib/assets/star-graph.svg';
</script>

<div class="flex justify-center">
	<Navbar class="max-w-6xl">
		<NavBrand href="/">
			<img src={StarGraph} class="me-3 h-6 sm:h-9" alt="Star Nest Logo" />
			<span class="self-center whitespace-nowrap text-xl font-semibold dark:text-white"
				>Star Nest</span
			>
		</NavBrand>
		<NavHamburger />
		<NavUl>
			<NavLi href="/">Home</NavLi>
			<NavLi href="/about">About</NavLi>
			<NavLi href="/contact">Contact</NavLi>
		</NavUl>
	</Navbar>
</div>
