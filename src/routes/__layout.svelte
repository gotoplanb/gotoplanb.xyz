<script>
	import '../app.css';
</script>

<header class="bg-gray-600">
	<nav class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8" aria-label="Top">
		<div
			class="w-full py-6 flex items-center justify-between border-b border-indigo-500 lg:border-none"
		>
			<div class="flex items-center">
				<div class="hidden ml-10 space-x-8 lg:block">
					<a href="/" class="text-base font-medium text-white hover:text-indigo-50">Gallery</a>

					<a href="/collections" class="text-base font-medium text-white hover:text-indigo-50"
						>Collections</a
					>

					<a href="/links" class="text-base font-medium text-white hover:text-indigo-50">Links</a>
				</div>
			</div>
			<div class="ml-10 space-x-4">
				<a
					href="#"
					class="inline-block bg-gray-500 py-2 px-4 border border-transparent rounded-md text-base font-medium text-white hover:bg-opacity-75"
					>Connect</a
				>
			</div>
		</div>
	</nav>
</header>

<slot />
