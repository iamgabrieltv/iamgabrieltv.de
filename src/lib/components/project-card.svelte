<script lang="ts">
 export let title: string;
 export let body: string;
</script>

<div class="card w-auto md:w-96 lg:w-96 bg-base-300 shadow-xl">
	<div class="card-body">
		<h2 class="card-title">{title}</h2>
		<p>{body}</p>
		<div class="card-actions justify-start">
			<a href="https://github.com/iamgabrieltv/IamChat">
				<button class="btn btn-primary">GitHub</button>
			</a>
		</div>
	</div>
</div>