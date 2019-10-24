<script>
	import Header from './Header.svelte'
	import Canvas from './Canvas/Index.svelte'
	
	export let header
</script>

<style lang="scss">
	.wrapper {
		margin-top: 2vh;
		display: grid;
		grid-template-columns: 15vw [content-start] 1fr [content-end] 15vw;
		grid-gap: 2rem;
	}
</style>

<div class="wrapper">
	<Header {header}/>
	<Canvas/>
</div>
