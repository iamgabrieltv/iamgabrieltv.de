<script>
	import ProjectCard from '$lib/components/project-card.svelte';
</script>

<h1 class="text-3xl font-bold">Projects</h1>
<p class="text-lg mb-3">Here you can check out my projects on GitHub!</p>

<div class="divider" />

<div class="grid gap-4 grid-cols-1 md:grid-cols-3">
	<ProjectCard
		title="IamBot"
		body="A very specific custom discord bot."
		url="https://github.com/iamgabrieltv/IamBot"
	/>
	<ProjectCard
		title="iamgabrieltv.tk"
		body="The Website you're on right now!"
		url="https://github.com/iamgabrieltv/iamgabrieltv.tk"
	/>
</div>
