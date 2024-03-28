<script lang="ts">
	function redirectToLinktree() {
		location.href = 'https://linktr.ee/tropicalsos';
	}
	function redirectToDiscord() {
		location.href = 'https://discord.gg/Sv2VwwXXRJ';
	}
	function redirectToDigitalStore() {
		location.href = 'https://master--tropicalsos-store.netlify.app/';
	}
</script>

<footer class="footer bg-neutral p-10 text-neutral-content">
	<nav>
		<h6 class="footer-title">Links</h6>
		<div class="grid grid-flow-col gap-4">
			<button class="btn font-mono" on:click={() => redirectToLinktree()}>Linktr.ee</button>
			<button class="btn font-mono" on:click={() => redirectToDiscord()}>Discord</button>
			<button class="btn font-mono" on:click={() => redirectToDigitalStore()}>Digital Store</button>
		</div>
	</nav>
</footer>
