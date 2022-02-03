<script>
	import { onMount } from 'svelte';

	onMount(async () => {
		await import('lite-youtube-embed/src/lite-yt-embed.css');
		await import('lite-youtube-embed/src/lite-yt-embed.js');
	});
</script>

<lite-youtube
	videoid="S7j0ZtXq7Go"
	style="background-image: url('https://i.ytimg.com/vi/S7j0ZtXq7Go/hqdefault.jpg');"
	params="rel=0&enablejsapi=1&modestbranding=1&autoplay=1"
/>
