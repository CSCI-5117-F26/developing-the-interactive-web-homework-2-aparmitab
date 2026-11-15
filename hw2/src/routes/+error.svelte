<script lang="ts">
	import { page } from '$app/state';
	import BackButton from './BackButton.svelte';
</script>

<section class="section">
<h1 class="title">{page.status}: {page.error?.message}</h1>

<BackButton/>
</section>