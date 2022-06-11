<script>
</script>
<main>
	<legend>Search For Character</legend>
	<div class="char">
	<label for="character">Character: </label>
	<input id="character" type="text" placeholder="start typing...">
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
		</div>
	<div class="display">
	<div>
	
	<h2>Full Name:</h2>
	<h2>Family:</h2>
	<h2>Title:</h2>
	<button>Generate Quote</button><div class="text"></div><textarea cols="30" rows="10" value="Hello World" readonly></textarea></div>
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
	.text{
		display:flex;
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
	}
	.display{
		display:flex;
		margin-left: 5rem;
	}
	.display-wrapper{
		display:flex;
	}
</style>