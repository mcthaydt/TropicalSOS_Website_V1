<!-- 2nd CTA -->
<script lang="ts">
	function redirectToDigitalStorefront() {
		location.href = 'https://master--tropicalsos-store.netlify.app';
	}
</script>

<div class="hero relative min-h-screen">
	<video
		src="/WebsiteVideo.mp4"
		autoplay
		loop
		muted
		class="absolute left-0 top-0 h-full w-full object-cover"
	/>
	<div class="hero-overlay bg-opacity-60"></div>
	<div class="hero-content text-center font-mono text-neutral-content">
		<div class="max-w-md">
			<h1 class="mb-5 text-5xl font-bold">Unleash Your Gaming Adventure</h1>
			<p class="mb-5">Explore Captivating Worlds While They're Still in Creation.</p>
			<button class="btn btn-primary font-mono" on:click={() => redirectToDigitalStorefront()}
				>Digital Storefront</button
			>
		</div>
	</div>
</div>
