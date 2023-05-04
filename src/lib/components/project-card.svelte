<script lang="ts">
	export let title: string;
	export let body: string;
	export let url: string;
</script>

<div class="card w-auto bg-base-300 shadow-xl transition-all hover:scale-105">
	<div class="card-body">
		<h2 class="card-title">{title}</h2>
		<p>{body}</p>
		<div class="card-actions justify-start">
			<a href={url}>
				<button class="btn btn-primary">GitHub</button>
			</a>
		</div>
	</div>
</div>
