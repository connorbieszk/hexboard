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

	<p>Please select a type of scouting below.</p>
	<div
		style="background-color: transparent;
      display: flex;
      margin: 2vh;
      justify-items: center;
      flex-direction: row;
    "
	>
		<a href={resolve("/scouting/match")} class="button"> Match Scout </a>
		<a href={resolve("/scouting/pit")} class="button-right"> Pit Scout </a>
		<a
			href={resolve("/scouting/practice")}
			class="button"
			style="
        margin-left: auto;
        "
		>
			Practice Scout
		</a>
		<a href={resolve("/scouting/prematch")} class="button-right"> Pre Scout </a>
		<a href={resolve("/scouting/offline")} class="button-right"> Offline Data </a>
	</div>
</div>
