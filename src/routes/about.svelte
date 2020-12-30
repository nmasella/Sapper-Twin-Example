<script>
	import { tw, setup } from 'twind';

	setup({
  		hash: true,
	});

	const styles = {
		center: tw`flex items-center justify-center`,
		bgcolor: tw`bg-indigo-400`
	}
</script>

<svelte:head>
	<title>About</title>
</svelte:head>

<h1>About this site</h1>

<p class="{tw `${styles.bgcolor} ${styles.center} text-white`}">This is the 'about' page. There's not much here.</p>