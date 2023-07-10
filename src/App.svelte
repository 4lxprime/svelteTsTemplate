<script lang="ts">
	let c = 0;
</script>

<main>
	<button on:click={()=>c++}>Count: {c}</button>
</main>

<style>
	main{
		text-align: center;
	}
</style>