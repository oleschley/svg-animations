<script>
    export let  header
</script>

<style lang="scss">
	$blue: hsl(203.2, 100, 20.8);
	
	header {
        font-size: 2rem;
		color: $blue;
        grid-column: content-start / content-end;
        justify-self: center;
	}

</style>


<header>
    <h1>{header}</h1>
</header>