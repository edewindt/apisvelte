<script>

	let quote = "Nothing for now";
	class GoTChar {
constructor(fullname,
firstname,
lastname,
title,
family,
image){
this.fullname
this.firstname
this.lastname
this.title
this.family
this.image

 }
	}

	let Khaleesi= {
		ID:1,
	fullname:'Daenerys Targaryen',
	firstname:'Daenerys',
	lastname:'Targaryen',
	title:'Mother of Dragons',
	family:'House Targaryen',
	image:'/build/images/khal.jpg'};
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
	<h2 id="ID">ID:{Khaleesi.ID}</h2>
	</div>
	<div class="display-wrapper">
	<div class="iamge">
		<img class= "iamge" src={Khaleesi.image} alt="">
		</div>
	<div class="display">
	<div>
		<h2>Full Name: {Khaleesi.fullname}</h2>
		<h2>Family: {Khaleesi.family}</h2>
		<h2>Title: {Khaleesi.title}</h2>

	<button class="butt">Generate Quote</button><div class="text"></div><textarea cols="30" rows="5" value={quote} readonly></textarea></div>
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
		clip-path: rect(450px);
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