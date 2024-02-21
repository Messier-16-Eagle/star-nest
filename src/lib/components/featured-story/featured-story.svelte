<script>
	/** @type {string} */
	export let image;
	/** @type {string} */
	export let title;
	/** @type {string} */
	export let subtitle;
	/** @type {string} */
	export let author;
	/** @type {string} */
	export let avatar;
	/** @type {string} */
	export let date;
	/** @type {string} */
	export let readingTime;
	/** @type {string} */
	export let href;
</script>

<a
	class="flex flex-col items-center justify-center rounded-lg bg-white p-4 shadow-lg dark:bg-gray-800 sm:flex-row"
	{href}
>
	<img src={image} class="h-64 w-full rounded-lg object-cover" alt={title} />
	<div class="flex w-full flex-col items-center justify-center p-4">
		<h2 class="text-2xl font-semibold text-gray-800 dark:text-white">{title}</h2>
		<p class="mt-2 text-sm text-gray-600 dark:text-gray-400">{subtitle}</p>
		<div class="mt-4 flex items-center justify-center space-x-2">
			<img src={avatar} class="h-8 w-8 rounded-full" alt={author} />
			<div class="flex flex-col items-start">
				<span class="text-sm font-semibold text-gray-800 dark:text-white">{author}</span>
				<span class="text-xs text-gray-500 dark:text-gray-400">{date} &bull; {readingTime}</span>
			</div>
		</div>
	</div>
</a>
