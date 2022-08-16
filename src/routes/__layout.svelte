<script>
	import '../app.css';
</script>

<!-- This example requires Tailwind CSS v2.0+ -->
<header class="bg-white">
	<nav class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8" aria-label="Top">
		<div
			class="w-full py-6 flex items-center justify-between border-b border-slate-600 lg:border-none"
		>
			<div class="flex items-center">
				<a href="/">
					<span>gotoplanb.xyz</span>
					<!-- TODO Add some logo maybe -->
					<!-- <span class="sr-only">gotoplanb.xyz</span>
			<img class="h-10 w-auto" src="https://tailwindui.com/img/logos/workflow-mark.svg?color=black" alt=""> -->
				</a>
				<div class="hidden ml-10 space-x-8 lg:block">
					<a href="/" class="text-base font-medium text-slate-600 hover:text-slate-800">
						Gallery
					</a>

					<a href="/collections" class="text-base font-medium text-slate-600 hover:text-slate-800">
						Collections
					</a>

					<a href="/links" class="text-base font-medium text-slate-600 hover:text-slate-800">
						Links
					</a>
				</div>
			</div>
			<div class="ml-10 space-x-4">
				<!-- <a href="#" class="inline-block bg-indigo-500 py-2 px-4 border border-transparent rounded-md text-base font-medium text-white hover:bg-opacity-75">Connect</a> -->
			</div>
		</div>
		<div class="py-4 flex flex-wrap justify-center space-x-6 lg:hidden">
			<a href="/" class="text-base font-medium text-slate-600 hover:text-slate-800"> Gallery </a>

			<a href="/collections" class="text-base font-medium text-slate-600 hover:text-slate-800">
				Collections
			</a>

			<a href="/links" class="text-base font-medium text-slate-600 hover:text-slate-800"> Links </a>
		</div>
	</nav>
</header>

<slot />
