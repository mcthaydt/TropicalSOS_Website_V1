<!-- Recent Projects -->
<script lang="ts">
	function redirectToPurchaseGame() {
		location.href = 'https://tropicalsos.itch.io/abyss-of-the-self';
	}
	function redirectToDevelopersPage() {
		location.href = 'https://www.fiverr.com/john_doom';
	}
</script>

<div class="carousel my-10 w-full">
	<div id="item1" class="carousel-item w-full flex-col">
		<img src="/AbyssOfTheSelfScreenshot3.png" class="mx-auto h-1/2 w-1/2" />
		<h1 class="my-10 mb-5 text-center font-mono text-5xl font-bold">Abyss of The Self</h1>
		<h3 class="mb-5 text-center font-mono text-xl font-bold">
			A recently deceased young man learns he can quickly acquire good karma by helping a local
			priest.
		</h3>
		<h3 class="mb-5 text-center font-mono text-xl">
			Developed by The Game Collective | March 2024
		</h3>
		<h3 class="mb-5 text-center font-mono text-xl">RPG-Maker Psychological Horror</h3>
		<div class="mx-auto max-w-screen-md flex-row">
			<button class="btn font-mono" on:click={() => redirectToPurchaseGame()}>Purchase</button>
			<button class="btn btn-neutral font-mono" on:click={() => redirectToDevelopersPage()}
				>Developer's Page</button
			>
		</div>
	</div>
</div>

<div class="flex w-full justify-center gap-2 py-2">
	<a href="#item1" class="btn btn-xs">1</a>
</div>
