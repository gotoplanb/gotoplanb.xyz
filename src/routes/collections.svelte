<script>
	import VideoPlayer from 'svelte-video-player';
</script>

<div class="grid grid-cols-2 ml-8">
	<div class="col-span-2">
		<h1 class="text-3xl font-bold">Collections</h1>
		<h2 class="text-xl font-bold">SINKHOLES</h2>
	</div>
	<div class="col-span-2">
		<p>Lorem ipsum</p>
	</div>
</div>

<!-- <VideoPlayer
	poster="./sinkholes-2022-august-devils-millhopper.png"
	source="./sinkholes-2022-august-devils-millhopper.m4v"
	loop
    color='#0021a5'
/> -->

<div class="grid grid-cols-2 md:grid-cols-12">
	<div class="col-span-2 md:col-span-6">
		<VideoPlayer
			poster="./sinkholes-2022-august-devils-millhopper.png"
			source="./sinkholes-2022-august-devils-millhopper.m4v"
			loop
			color="#0021a5"
		/>
	</div>
</div>
