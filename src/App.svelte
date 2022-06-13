<script>
	import Khal from './Khal.svelte';
	import Images from './Images.svelte';
	// let quote = "Nothing for now";
	// let Khaleesi= {
	// ID:1,
	// fullname:'Daenerys Targaryen',
	// firstname:'Daenerys',
	// lastname:'Targaryen',
	// title:'Mother of Dragons',
	// family:'House Targaryen',
	// image:'/build/images/khal.jpg'};
		let searchq = '';
		let Khalessi = 'Khaleesi';
</script>
<main>
	<legend>Search For Character</legend>
	<div class="char">
	<label for="character">Character: </label>
	<input bind:value={searchq} id="character" type="text" placeholder="start typing...">
	<label for="series">Series: </label>
	<select name="series" id="series">
		<option value="all">All</option>
		<option value="LoR">Lord Of the Rings</option>
		<option value="GoT">Game Of Thrones</option>
		<option value="SW">Star Wars</option>
	</select>
	<h2 id="ID">ID:</h2>
	</div>
	<div class="display-wrapper">
	<div class="iamge">
		{#if searchq === 'Khaleesi'}
		<Images/>
		{/if}
		</div>
	<div class="display">
	<div>
		{#if searchq === 'Khaleesi' || searchq === 'Sad'}
		<Khal/>
		{:else}
		<h2 id="name">Full Name:</h2>
    	<h2 id="family">Family: </h2>
    	<h2 id="title">Title: </h2>
		{/if}
	<button class="butt">Generate Quote</button><div class="text"></div><textarea cols="30" rows="5" value="" readonly></textarea></div>
</div>
</div>
</main>
<style>
	main{
		margin: 2rem;
	}
	legend{
		font-size: 2rem;
		margin-bottom: 1rem;
	}
	.butt{
		width: 20rem;
		border-radius: 1rem;
		background-color: orangered;
		color: aliceblue;
		border:0px;
		font-size: 1.5rem;
	}
	.text{
		display:flex;
	}
	textarea{
		font-size: 1.5rem;
		border-radius: 1rem;
	}
	#series{
		border-radius: 1rem;
	}
	#character{
		border-radius: 1rem;
	}
	#ID{
		display: inline;
	}
	.char{
		font-size: 1.5rem;
		margin-top: 2rem;
		margin-bottom: 2rem;
	}
	.iamge{
		height: 450px;
		width: 450px;
		background-color: black;
		border-radius: 1rem;
	}
	.display{
		display:flex;
		margin-left: 5rem;
	}
	.display-wrapper{
		display:flex;
		align-items: center;
	}
</style>