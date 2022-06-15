<script>
		//----------Game of Thones Components-------------------->>>>>>>>>
	import Khaleesi from './Characters/GoT/Khaleesi.svelte';
		import ImagesK from './CharacterImages/GoT/ImagesK.svelte';
	import Eddard from './Characters/GoT/Eddard.svelte'
		import ImagesNed from './CharacterImages/GoT/ImagesNed.svelte'
	import Arya from './Characters/GoT/Arya.svelte'
		import ImagesAr from './CharacterImages/GoT/ImagesAr.svelte'
	import Sansa from './Characters/GoT/Sansa.svelte'
		import ImagesSa from './CharacterImages/GoT/ImagesSa.svelte'
	import Brienne from './Characters/GoT/Brienne.svelte'
		import ImagesBr from './CharacterImages/GoT/ImagesBr.svelte';
	import Oberyn from './Characters/GoT/Oberyn.svelte'
		import ImagesOb from './CharacterImages/GoT/ImagesOb.svelte'
	import Ramsey from './Characters/GoT/Ramsey.svelte'
		import ImagesRa from './CharacterImages/GoT/ImagesRa.svelte'
	import Gilly from './Characters/GoT/Gilly.svelte'
		import ImagesGi from './CharacterImages/GoT/ImagesGi.svelte'
	import Daario from './Characters/GoT/Daario.svelte'
		import ImagesDa from './CharacterImages/GoT/ImagesDa.svelte'
	import Missandei from './Characters/GoT/Missandei.svelte'
		import ImagesMi from './CharacterImages/GoT/ImagesMi.svelte'
	import Ellaria from './Characters/GoT/Ellaria.svelte'
		import ImagesEl from './CharacterImages/GoT/ImagesEl.svelte'
	import Euron from './Characters/GoT/Euron.svelte'
		import ImagesEu from './CharacterImages/GoT/ImagesEu.svelte'
	import Wylis from './Characters/GoT/Wylis.svelte'
		import ImagesWy from './CharacterImages/GoT/ImagesWy.svelte'
	import Tommen from './Characters/GoT/Tommen.svelte'
		import ImagesTo from './CharacterImages/GoT/ImagesTo.svelte'
	import Jaqen from './Characters/GoT/Jaqen.svelte'
		import ImagesJa from './CharacterImages/GoT/ImagesJa.svelte'
	import Roose from './Characters/GoT/Roose.svelte'
		import ImagesRo from './CharacterImages/GoT/ImagesRo.svelte'
	import Sparrow from './Characters/GoT/Sparrow.svelte'
		import ImagesSp from './CharacterImages/GoT/ImagesSp.svelte'
	import Grey from './Characters/GoT/Grey.svelte'
		import ImagesGr from './CharacterImages/GoT/ImagesGr.svelte'
	import Olenna from './Characters/GoT/Olenna.svelte'
		import ImagesOl from './CharacterImages/GoT/ImagesOl.svelte'
	import Qyburn from './Characters/GoT/Qyburn.svelte'
		import ImagesQy from './CharacterImages/GoT/ImagesQy.svelte'
	import Tormund from './Characters/GoT/Tormund.svelte'
		import ImagesTor from './CharacterImages/GoT/ImagesTor.svelte'
	import Yara from './Characters/GoT/Yara.svelte'
		import ImagesYa from './CharacterImages/GoT/ImagesYa.svelte'
	import Rickon from './Characters/GoT/Rickon.svelte'
		import ImagesRi from './CharacterImages/GoT/ImagesRi.svelte'
	import Melisandre from './Characters/GoT/Melisandre.svelte'
		import ImagesMel from './CharacterImages/GoT/ImagesMel.svelte'
	import Jeor from './Characters/GoT/Jeor.svelte'
		import ImagesJe from './CharacterImages/GoT/ImagesJe.svelte'
	import Bronn from './Characters/GoT/Bronn.svelte'
		import ImagesBro from './CharacterImages/GoT/ImagesBro.svelte'
	import Theon from './Characters/GoT/Theon.svelte'
		import ImagesTh from './CharacterImages/GoT/ImagesTh.svelte'
	import Varys from './Characters/GoT/Varys.svelte'
		import ImagesVa from './CharacterImages/GoT/ImagesVa.svelte'
	import Shae from './Characters/GoT/Shae.svelte'
		import ImagesSh from './CharacterImages/GoT/ImagesSh.svelte'
	import Pycelle from './Characters/GoT/Pycelle.svelte'
		import ImagesPy from './CharacterImages/GoT/ImagesPy.svelte'
	import Margaery from './Characters/GoT/Margaery.svelte'
		import ImagesMar from './CharacterImages/GoT/Imagesmar.svelte'
	import Tywin from './Characters/GoT/Tywin.svelte'
		import ImagesTy from './CharacterImages/GoT/ImagesTy.svelte'
	import Talisa from './Characters/GoT/Talisa.svelte'
		import ImagesTa from './CharacterImages/GoT/ImagesTa.svelte'
	import Ygritte from './Characters/GoT/Ygritte.svelte'
		import ImagesYg from './CharacterImages/GoT/ImagesYg.svelte'
	import Gendry from './Characters/GoT/Gendry.svelte'
		import ImagesGe from './CharacterImages/GoT/ImagesGe.svelte'
	import Jorah from './Characters/GoT/Jorah.svelte'
		import ImagesJor from './CharacterImages/GoT/ImagesJor.svelte'
	import Robert from './Characters/GoT/Robert.svelte'
		import ImagesRob from './CharacterImages/GoT/ImagesRob.svelte'
	import Jaime from './Characters/GoT/Jaime.svelte'
		import ImagesJai from './CharacterImages/GoT/ImagesJai.svelte'
	import Catelyn from './Characters/GoT/Catelyn.svelte'
		import ImagesCa from './CharacterImages/GoT/ImagesCa.svelte'
	import Robb from './Characters/GoT/Robb.svelte'
		import ImagesR from './CharacterImages/GoT/ImagesR.svelte'
	import Cersei from './Characters/GoT/Cersei.svelte'
		import ImagesCe from './CharacterImages/GoT/ImagesCe.svelte'
	import Jon from './Characters/GoT/Jon.svelte'
		import ImagesJo from './CharacterImages/GoT/ImagesJo.svelte'
	import Joffrey from './Characters/GoT/Joffrey.svelte'
		import ImagesJof from './CharacterImages/GoT/ImagesJof.svelte'
	import Sandor from './Characters/GoT/Sandor.svelte'
		import ImagesSan from './CharacterImages/GoT/ImagesSan.svelte'
	import Tyrion from './Characters/GoT/Tyrion.svelte'
		import ImagesTyr from './CharacterImages/GoT/ImagesTyr.svelte'
	import Petyr from './Characters/GoT/Petyr.svelte'
		import ImagesPe from './CharacterImages/GoT/ImagesPe.svelte'
	import Davos from './Characters/Got/Davos.svelte'
		import ImagesDav from './CharacterImages/GoT/ImagesDav.svelte'
	import Samwell from './Characters/GoT/Samwell.svelte'
		import ImagesSam from './CharacterImages/GoT/ImagesSam.svelte'
	import Brandon from './Characters/GoT/Brandon.svelte'
		import ImagesBra from './CharacterImages/GoT/ImagesBra.svelte'
	import Stannis from './Characters/GoT/Stannis.svelte'
		import ImagesSt from './CharacterImages/GoT/ImagesSt.svelte'
	import Viserys from './Characters/GoT/Viserys.svelte'
		import ImagesVi from './CharacterImages/GoT/ImagesVi.svelte'
	import Khal from './Characters/GoT/Khal.svelte'
		import ImagesKh from './CharacterImages/GoT/ImagesKh.svelte'
		//----------Star Wars Components-------------------->>>>>>>>>
	import Yoda from './Characters/SW/Yoda.svelte';
		import ImagesY from './CharacterImages/SW/ImagesY.svelte';
		//----------One Punch Man Components-------------------->>>>>>>>>
	import OnePunch from './Characters/OPM/OnePunch.svelte';
		import ImagesO from './CharacterImages/OPM/ImagesO.svelte';
		//----------JoJos Components-------------------->>>>>>>>>
	
		let searchq = '';
</script>
<main>
	<legend>Search For Character</legend>
	<div class="char">
	<label for="character">Character: </label>
	<input bind:value={searchq} id="character" type="text" placeholder="start typing...">
	<h2 id="ID">ID:</h2>
	</div>
	<div class="display-wrapper">
	<div class="iamge">
		<!---------------Game Of Thrones If Statements--------------------->
		{#if searchq === 'Khaleesi' || searchq === 'Daenerys' || searchq === 'Daenerys Targaryen'|| searchq === 'khaleesi'|| searchq === 'daenerys' || searchq === 'daenerys targaryen'}
		<ImagesK/>
		{:else if searchq === 'Eddard' || searchq === 'Ned' || searchq === 'Eddard Stark'|| searchq === 'ned'|| searchq === 'eddard stark'|| searchq === 'eddard'}
		<ImagesNed/>
		{:else if searchq === 'Sansa' || searchq === 'sansa' || searchq === 'Sansa Stark'|| searchq === 'sansa stark'}
		<ImagesSa/>
		{:else if searchq === 'Arya' || searchq === 'arya' || searchq === 'Arya Stark'|| searchq === 'arya stark'}
		<ImagesAr/>
		{:else if searchq === 'Brienne' || searchq === 'brienne' || searchq === 'Brienne Of Tarth'|| searchq === 'brienne of tarth'}
		<ImagesBr/>
		{:else if searchq === 'Oberyn' || searchq === 'oberyn' || searchq === 'Oberyn Martell'||searchq === 'oberyn martell'}
		<ImagesOb/>
		{:else if searchq === 'Ramsey' || searchq === 'ramsey' || searchq === 'Ramsey Bolton'|| searchq === 'ramsey bolton'}
		<ImagesRa/>
		{:else if searchq === 'Gilly' || searchq === 'gilly'}
		<ImagesGi/>
		{:else if searchq === 'Daario' || searchq === 'daario' || searchq === 'Daario Naharis'|| searchq === 'daario naharis'}
		<ImagesDa/>
		{:else if searchq === 'Missandei' || searchq === 'missandei'}
		<ImagesMi/>
		{:else if searchq === 'Ellaria' || searchq === 'ellaria' || searchq === 'Ellaria Sand'|| searchq === 'ellaria sand'}
		<ImagesEl/>
		{:else if searchq === 'Euron' || searchq === 'euron' || searchq === 'Euron Greyjoy'|| searchq === 'euron greyjoy'}
		<ImagesEu/>
		{:else if searchq === 'Wylis' || searchq === 'wylis' || searchq === 'Wylis Hodor'|| searchq === 'wylis hodor'}
		<ImagesWy/>
		{:else if searchq === 'Tommen' || searchq === 'tommen' || searchq === 'Tommen Baratheon'|| searchq === 'tommen baratheon'}
		<ImagesTo/>
		{:else if searchq === 'Grey' || searchq === 'grey' || searchq === 'Grey Worm'|| searchq === 'grey worm'}
		<ImagesGr/>
		{:else if searchq === 'Jaqen' || searchq === 'jaqen' || searchq === 'Jaqen H\'ghar'|| searchq === 'jaqen h\'ghar'}
		<ImagesJa/>
		{:else if searchq === 'Roose' || searchq === 'roose' || searchq === 'Roose Bolton'|| searchq === 'roose bolton'}
		<ImagesRo/>
		{:else if searchq === 'sparrow' || searchq === 'Sparrow'|| searchq === 'The High Sparrow'|| searchq === 'the higher sparrow'|| searchq === 'the high'||searchq === 'The High'}
		<ImagesSp/>
		{:else if searchq === 'Olenna Tyrell' || searchq === 'olenna tyrell'|| searchq === 'olenna'|| searchq === 'Olenna'}
		<ImagesOl/>
		{:else if searchq === 'Qyburn' || searchq === 'qyburn'|| searchq === 'Qyburn Grand Maester'|| searchq === 'qyburn grand maester'}
		<ImagesQy/>
		{:else if searchq === 'Tormund Giantsbane' || searchq === 'tormund giantsbane'|| searchq === 'Tormund'|| searchq === 'tormund'}
		<ImagesTor/>
		{:else if searchq === 'Yara' || searchq === 'yara'|| searchq === 'Yara Greyjoy'|| searchq === 'yara greyjoy'}
		<ImagesYa/>
		{:else if searchq === 'Rickon Stark' || searchq === 'rickon stark'|| searchq === 'rickon'|| searchq === 'Rickon'}
		<ImagesRi/>
		{:else if searchq === 'Melisandre' || searchq === 'melisandre'|| searchq === 'Melisandre The Red Woman'|| searchq === 'melisandre the red woman'}
		<ImagesMel/>
		{:else if searchq === 'Jeor' || searchq === 'jeor'|| searchq === 'jeor mormont'|| searchq === 'Jeor Mormont'}
		<ImagesJe/>
		{:else if searchq === 'Bronn' || searchq === 'bronn'|| searchq === 'Lord Bronn'|| searchq === 'lord bronn'}
		<ImagesBro/>
		{:else if searchq === 'Theon Greyjoy' || searchq === 'theon greyjoy'|| searchq === 'theon'|| searchq === 'Theon'}
		<ImagesTh/>
		{:else if searchq === 'Varys' || searchq === 'varys'}
		<ImagesVa/>
		{:else if searchq === 'Shae' || searchq === 'shae'}
		<ImagesSh/>
		{:else if searchq === 'Pycelle' || searchq === 'pycelle'}
		<ImagesPy/>
		{:else if searchq === 'Margaery' || searchq === 'margaery'||searchq === 'Margaery Tyrell'|| searchq === 'margaery tyrell'}
		<ImagesMar/>
		{:else if searchq === 'Tywin' || searchq === 'tywin'||searchq === 'Tywin Lannister'|| searchq === 'tywin lannister'}
		<ImagesTy/>
		{:else if searchq === 'Talisa' || searchq === 'talisa'||searchq === 'Talisa Stark'|| searchq === 'talisa stark'}
		<ImagesTa/>
		{:else if searchq === 'Ygritte' || searchq === 'ygritte'}
		<ImagesYg/>
		{:else if searchq === 'Gendry Baratheon' || searchq === 'gendry baratheon'||searchq === 'gendry'|| searchq === 'Gendry'}
		<ImagesGe/>
		{:else if searchq === 'Jorah Mormont' || searchq === 'jorah mormont'||searchq === 'Jorah'|| searchq === 'jorah'}
		<ImagesJor/>
		{:else if searchq === 'Robert Baratheon' || searchq === 'robert baratheon'|| searchq === 'Robert'|| searchq === 'robert'}
		<ImagesRob/>
		{:else if searchq === 'jaime' || searchq === 'Jaime'||searchq === 'Jaime Lannister'||searchq === 'jaime lannister'}
		<ImagesJai/>
		{:else if searchq === 'Catelyn' || searchq === 'catelyn'||searchq === 'Catelyn Stark'||searchq === 'catelyn stark'}
		<ImagesCa/>
		{:else if searchq === 'Robb' || searchq === 'robb'|| searchq === 'Robb Stark'|| searchq === 'robb stark'}
		<ImagesR/>
		{:else if searchq === 'Cersei Lannister' || searchq === 'cersei lannister'|| searchq === 'Cersei'|| searchq === 'cersei'}
		<ImagesCe/>
		{:else if searchq === 'Jon Snow' || searchq === 'jon snow'|| searchq === 'Jon'|| searchq === 'jon'}
		<ImagesJo/>
		{:else if searchq === 'joffrey baratheon' || searchq === 'Joffrey Baratheon'|| searchq === 'joffrey'|| searchq === 'Joffrey'}
		<ImagesJof/>
		{:else if searchq === 'Sandor' || searchq === 'sandor'|| searchq === 'Sandor Clegane'|| searchq === 'sandor clegane'}
		<ImagesSan/>
		{:else if searchq === 'Tyrion' || searchq === 'tyrion'|| searchq === 'Tyrion Lannister'|| searchq === 'tyrion lannister'}
		<ImagesTyr/>
		{:else if searchq === 'Petyr Baelish' || searchq === 'petyr baelish'|| searchq === 'Petyr'|| searchq === 'petyr'}
		<ImagesPe/>
		{:else if searchq === 'Davos' || searchq === 'davos'|| searchq === 'Davos Seaworth'|| searchq === 'davos seaworth'}
		<ImagesDav/>
		{:else if searchq === 'samwell' || searchq === 'Samwell'|| searchq === 'Samwell Tarly'|| searchq === 'samwell tarly' || searchq === 'sam' || searchq === 'Sam'}
		<ImagesSam/>
		{:else if searchq === 'Brandon' || searchq === 'brandon'|| searchq === 'Brandon Stark'|| searchq === 'brandon stark'}
		<ImagesBra/>
		{:else if searchq === 'Stannis' || searchq === 'stannis'|| searchq === 'Stannis Baratheon'|| searchq === 'stannis baratheon'}
		<ImagesSt/>
		{:else if searchq === 'Viserys Targaryn' || searchq === 'viserys targaryn'|| searchq === 'Viserys'|| searchq === 'viserys'}
		<ImagesVi/>
		{:else if searchq === 'Khal' || searchq === 'khal'|| searchq === 'Khal Drogo'|| searchq === 'khal drogo'}
		<ImagesKh/>
		<!---------------Starwars If Statements--------------------->
		{:else if searchq === 'Yoda' || searchq === 'Minch' || searchq === 'Minch Yoda'|| searchq === 'yoda'||searchq === 'mich'||searchq === 'minch yoda'}
		<ImagesY/>
		<!---------------One Punch Man If Statements--------------------->
		{:else if searchq === 'One Punch Man' || searchq === 'Saitama' || searchq === 'Caped Baldy'|| searchq === 'saitama'||searchq === 'one punch man'|| searchq === 'caped baldy'}
		<ImagesO/>
		{/if}
		</div>
	<div class="display">
	<div>
		<!---------------Game Of Thrones If Statements--------------------->
		{#if searchq === 'Khaleesi' || searchq === 'Daenerys' || searchq === 'Daenerys Targaryen'|| searchq === 'khaleesi'|| searchq === 'daenerys' || searchq === 'daenerys targaryen'}
		<Khaleesi/>
		{:else if searchq === 'Eddard' || searchq === 'Ned' || searchq === 'Eddard Stark'|| searchq === 'ned'|| searchq === 'eddard stark'|| searchq === 'eddard'}
		<Eddard/>
		{:else if searchq === 'Sansa' || searchq === 'sansa' || searchq === 'Sansa Stark'|| searchq === 'sansa stark'}
		<Sansa/>
		{:else if searchq === 'Arya' || searchq === 'arya' || searchq === 'Arya Stark'|| searchq === 'arya stark'}
		<Arya/>
		{:else if searchq === 'Brienne' || searchq === 'brienne' || searchq === 'Brienne Of Tarth'|| searchq === 'brienne of tarth'}
		<Brienne/>
		{:else if searchq === 'Oberyn' || searchq === 'oberyn' || searchq === 'Oberyn Martell'||searchq === 'oberyn martell'}
		<Oberyn/>
		{:else if searchq === 'Ramsey' || searchq === 'ramsey' || searchq === 'Ramsey Bolton'|| searchq === 'ramsey bolton'}
		<Ramsey/>
		{:else if searchq === 'Gilly' || searchq === 'gilly'}
		<Gilly/>
		{:else if searchq === 'Daario' || searchq === 'daario' || searchq === 'Daario Naharis'|| searchq === 'daario naharis'}
		<Daario/>
		{:else if searchq === 'Missandei' || searchq === 'missandei'}
		<Missandei/>
		{:else if searchq === 'Ellaria' || searchq === 'ellaria' || searchq === 'Ellaria Sand'|| searchq === 'ellaria sand'}
		<Ellaria/>
		{:else if searchq === 'Euron' || searchq === 'euron' || searchq === 'Euron Greyjoy'|| searchq === 'euron greyjoy'}
		<Euron/>
		{:else if searchq === 'Wylis' || searchq === 'wylis' || searchq === 'Wylis Hodor'|| searchq === 'wylis hodor'}
		<Wylis/>
		{:else if searchq === 'Tommen' || searchq === 'tommen' || searchq === 'Tommen Baratheon'|| searchq === 'tommen baratheon'}
		<Tommen/>
		{:else if searchq === 'Jaqen' || searchq === 'jaqen' || searchq === 'Jaqen H\'ghar'|| searchq === 'jaqen h\'ghar'}
		<Jaqen/>
		{:else if searchq === 'Roose' || searchq === 'roose' || searchq === 'Roose Bolton'|| searchq === 'roose bolton'}
		<Roose/>
		{:else if searchq === 'sparrow' || searchq === 'Sparrow'|| searchq === 'The High Sparrow'|| searchq === 'the higher sparrow'|| searchq === 'the high'||searchq === 'The High'}
		<Sparrow/>
		{:else if searchq === 'Grey Worm' || searchq === 'grey worm'|| searchq === 'grey'|| searchq === 'Grey'}
		<Grey/>
		{:else if searchq === 'Olenna Tyrell' || searchq === 'olenna tyrell'|| searchq === 'olenna'|| searchq === 'Olenna'}
		<Olenna/>
		{:else if searchq === 'Qyburn' || searchq === 'qyburn'|| searchq === 'Qyburn Grand Maester'|| searchq === 'qyburn grand maester'}
		<Qyburn/>
		{:else if searchq === 'Tormund Giantsbane' || searchq === 'tormund giantsbane'|| searchq === 'Tormund'|| searchq === 'tormund'}
		<Tormund/>
		{:else if searchq === 'Yara' || searchq === 'yara'|| searchq === 'Yara Greyjoy'|| searchq === 'yara greyjoy'}
		<Yara/>
		{:else if searchq === 'Rickon Stark' || searchq === 'rickon stark'|| searchq === 'rickon'|| searchq === 'Rickon'}
		<Rickon/>
		{:else if searchq === 'Melisandre' || searchq === 'melisandre'|| searchq === 'Melisandre The Red Woman'|| searchq === 'melisandre the red woman'}
		<Melisandre/>
		{:else if searchq === 'Jeor' || searchq === 'jeor'|| searchq === 'jeor mormont'|| searchq === 'Jeor Mormont'}
		<Jeor/>
		{:else if searchq === 'Bronn' || searchq === 'bronn'|| searchq === 'Lord Bronn'|| searchq === 'lord bronn'}
		<Bronn/>
		{:else if searchq === 'Theon Greyjoy' || searchq === 'theon greyjoy'|| searchq === 'theon'|| searchq === 'Theon'}
		<Theon/>
		{:else if searchq === 'Varys' || searchq === 'varys'}
		<Varys/>
		{:else if searchq === 'Shae' || searchq === 'shae'}
		<Shae/>
		{:else if searchq === 'Pycelle' || searchq === 'pycelle'}
		<Pycelle/>
		{:else if searchq === 'Margaery' || searchq === 'margaery'||searchq === 'Margaery Tyrell'|| searchq === 'margaery tyrell'}
		<Margaery/>
		{:else if searchq === 'Tywin' || searchq === 'tywin'||searchq === 'Tywin Lannister'|| searchq === 'tywin lannister'}
		<Tywin/>
		{:else if searchq === 'Talisa' || searchq === 'talisa'||searchq === 'Talisa Stark'|| searchq === 'talisa stark'}
		<Talisa/>
		{:else if searchq === 'Ygritte' || searchq === 'ygritte'}
		<Ygritte/>
		{:else if searchq === 'Gendry Baratheon' || searchq === 'gendry baratheon'||searchq === 'gendry'|| searchq === 'Gendry'}
		<Gendry/>
		{:else if searchq === 'Jorah Mormont' || searchq === 'jorah mormont'||searchq === 'Jorah'|| searchq === 'jorah'}
		<Jorah/>
		{:else if searchq === 'Robert Baratheon' || searchq === 'robert baratheon'|| searchq === 'Robert'|| searchq === 'robert'}
		<Robert/>
		{:else if searchq === 'jaime' || searchq === 'Jaime'||searchq === 'Jaime Lannister'||searchq === 'jaime lannister'}
		<Jaime/>
		{:else if searchq === 'Catelyn' || searchq === 'catelyn'||searchq === 'Catelyn Stark'||searchq === 'catelyn stark'}
		<Catelyn/>
		{:else if searchq === 'Robb' || searchq === 'robb'|| searchq === 'Robb Stark'|| searchq === 'robb stark'}
		<Robb/>
		{:else if searchq === 'Cersei Lannister' || searchq === 'cersei lannister'|| searchq === 'Cersei'|| searchq === 'cersei'}
		<Cersei/>
		{:else if searchq === 'Jon Snow' || searchq === 'jon snow'|| searchq === 'Jon'|| searchq === 'jon'}
		<Jon/>
		{:else if searchq === 'joffrey baratheon' || searchq === 'Joffrey Baratheon'|| searchq === 'joffrey'|| searchq === 'Joffrey'}
		<Joffrey/>
		{:else if searchq === 'Sandor' || searchq === 'sandor'|| searchq === 'Sandor Clegane'|| searchq === 'sandor clegane'}
		<Sandor/>
		{:else if searchq === 'Tyrion' || searchq === 'tyrion'|| searchq === 'Tyrion Lannister'|| searchq === 'tyrion lannister'}
		<Tyrion/>
		{:else if searchq === 'Petyr Baelish' || searchq === 'petyr baelish'|| searchq === 'Petyr'|| searchq === 'petyr'}
		<Petyr/>
		{:else if searchq === 'Davos' || searchq === 'davos'|| searchq === 'Davos Seaworth'|| searchq === 'davos seaworth'}
		<Davos/>
		{:else if searchq === 'samwell' || searchq === 'Samwell'|| searchq === 'Samwell Tarly'|| searchq === 'samwell tarly' || searchq === 'sam' || searchq === 'Sam'}
		<Samwell/>
		{:else if searchq === 'Brandon' || searchq === 'brandon'|| searchq === 'Brandon Stark'|| searchq === 'brandon stark'}
		<Brandon/>
		{:else if searchq === 'Stannis' || searchq === 'stannis'|| searchq === 'Stannis Baratheon'|| searchq === 'stannis baratheon'}
		<Stannis/>
		{:else if searchq === 'Viserys Targaryn' || searchq === 'viserys targaryn'|| searchq === 'Viserys'|| searchq === 'viserys'}
		<Viserys/>
		{:else if searchq === 'Khal' || searchq === 'khal'|| searchq === 'Khal Drogo'|| searchq === 'khal drogo'}
		<Khal/>
		<!---------------Starwars If Statements--------------------->
		{:else if searchq === 'Yoda' || searchq === 'Minch' || searchq === 'Minch Yoda'|| searchq === 'yoda'||searchq === 'mich'||searchq === 'minch yoda'}
		<Yoda/>
		<!---------------One Punch Man If Statements--------------------->
		{:else if searchq === 'One Punch Man' || searchq === 'Saitama' || searchq === 'Caped Baldy'|| searchq === 'saitama'||searchq === 'one punch man'|| searchq === 'caped baldy'}
		<OnePunch/>
		{:else}
		<h2 id="name">Full Name:</h2>
		<h2 id="title">Title: </h2>
    	<h2 id="family">Family: </h2>
		<h2 id="gender">Gender: </h2>
		{/if}
	<button class="butt">Generate Quote</button><div class="text"></div><textarea cols="30" rows="5" value="" readonly></textarea></div>
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