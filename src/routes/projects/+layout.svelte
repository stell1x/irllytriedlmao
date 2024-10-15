<script>
	import ProjectsBar from '$lib/components/other/projectsBar.svelte';
</script>

<div class="projectsWrapper flex mt-5">
	<ProjectsBar />
	<slot />
</div>

<style>
	@media screen and (max-width: 600px) {
        .projectsWrapper {
            display: block !important;
        }
	}
</style>
