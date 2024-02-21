<script>
	import { Footer, FooterCopyright, FooterLink, FooterLinkGroup } from 'flowbite-svelte';
</script>

<Footer class="mt-4">
	<FooterCopyright
		spanClass="block text-sm text-gray-500 text-center dark:text-gray-400"
		href="/"
		by="Star Nest"
		year={2024}
	/>
	<FooterLinkGroup
		ulClass="flex flex-wrap items-center justify-center mt-3 text-sm text-gray-500 dark:text-gray-400 sm:mt-0"
	>
		<FooterLink href="/about">About</FooterLink>
		<FooterLink href="/privacy">Privacy Policy</FooterLink>
		<FooterLink href="/contact">Contact</FooterLink>
	</FooterLinkGroup>
</Footer>
