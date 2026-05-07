<script>
	  import { resolve } from '$app/paths';
</script>

<div class="content">
	<h1
		style="
    background-color: var(--bg-color-3);
    padding: 2vh;
    margin: 2vh;
    "
	>
		Welcome Scouter!
	</h1>

	<p>Please select a scouting related menu. Offline Data holds all the data for each type of scouting that needs to be upload still. </p>
	<div class="button-menu">
		<a href={resolve("/scouting/match")}    class="button"> Match Scout </a>
		<a href={resolve("/scouting/pit")}      class="button-center"> Pit Scout </a>
		<a href={resolve("/scouting/practice")} class="button-center" >Practice Scout</a>
		<a href={resolve("/scouting/prematch")} class="button-center"> Pre Scout </a>
		<a href={resolve("/scouting/offline")}  class="button-right"> Offline Data </a>
	</div>
</div>
