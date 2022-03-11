<script>
	import { onMount } from 'svelte';

	onMount(() => {
		import('lite-youtube-embed/src/lite-yt-embed.js');
		import('lite-youtube-embed/src/lite-yt-embed.css');
	});
</script>

<lite-youtube videoid="S7j0ZtXq7Go" />
