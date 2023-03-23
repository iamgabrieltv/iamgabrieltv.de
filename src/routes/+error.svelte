<script>
	import { page } from '$app/stores';

	function pop() {
		var pop = new Audio('/pop.mp3');
		pop.play();
	}
</script>

<div class="flex flex-col items-center mt-24">
	<h1 class="font-bold text-4xl text-error mb-2">Error</h1>
	<h1 class="font-bold text-4xl">{$page.status}</h1>
	<h1 class="font-bold text-2xl mb-4">{$page.error?.message}</h1>

	<div
		on:pointerover={pop}
		class="bg-[url(/closed.jpg)] hover:bg-[url(/open.jpg)] bg-cover w-20 h-20 hover:w-40 hover:h-40 hover:rotate-[360deg] transition-all"
	/>
</div>
