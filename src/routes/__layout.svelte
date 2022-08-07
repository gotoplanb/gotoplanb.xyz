<script>
	import '../app.css';
</script>

<header class="">
	<nav class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8" aria-label="Top">
		<div class="w-full py-4 flex items-center justify-between">
			<div class="flex items-center">
				<div class="hidden space-x-8 lg:block text-base font-medium text-slate-600 hover:text-slate-800">
					<a href="/">gotoplanb.xyz</a>
					<a href="/">Gallery</a>
					<a href="/collections">Collections</a>
					<a href="/links">Links</a>
				</div>
			</div>
			<div class="ml-10 space-x-4">
				<a
					href="#"
					class="inline-block bg-slate-600 py-2 px-4 border border-transparent rounded-md text-base font-medium text-white hover:bg-slate-700"
					>Connect</a
				>
			</div>
		</div>
	</nav>
</header>

<slot />
