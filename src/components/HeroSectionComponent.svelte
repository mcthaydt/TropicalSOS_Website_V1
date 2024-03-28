<!-- Hero -->

<script lang="ts">
	function redirectToIncubationLink() {
		location.href = 'https://airtable.com/appXHTA7AlnHepg5g/pagAC8lXi0DL9rz8e/form';
	}
</script>

<div class="hero relative min-h-screen">
	<video
		src="/HeroHeader.mp4"
		autoplay
		loop
		muted
		class="absolute left-0 top-0 h-full w-full object-cover"
	/>
	<div class="hero-overlay bg-black bg-opacity-60"></div>
	<div class="hero-content text-center text-neutral-content">
		<div class="max-w-md">
			<h1 class="mb-5 font-mono text-5xl font-bold">Elevate Your Game: Unlock Funding Success</h1>
			<p class="mb-5 font-mono">
				At TropicalSOS, we partner with developers to craft captivating, data-driven prototypes and
				vertical slices that compel investors and secure full funding for your game project.
			</p>
			<button class="btn btn-primary font-mono" on:click={() => redirectToIncubationLink()}
				>Incubation Application</button
			>
		</div>
	</div>
</div>
