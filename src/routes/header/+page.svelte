<script>
	import Header from "$lib/header.svelte";
	import NavItem from "$lib/navMenu/navItem.svelte";
</script>

<div class="headerContainer">
	<Header>
		<NavItem on:click={()=>{console.log("Home")}}><span class="item">Home</span></NavItem>
		<NavItem on:click={()=>{console.log("item1")}}><span class="item">item1</span></NavItem>
		<NavItem on:click={()=>{console.log("item2")}}><span class="item">item2</span></NavItem>
	</Header>
</div>

<style>
	.headerContainer {
		height: 4.5rem;
	}
	.item {
		font-size: 1.4rem;
	}
</style>