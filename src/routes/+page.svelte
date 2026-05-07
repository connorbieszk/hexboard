    <script>
  import { resolve } from '$app/paths';
</script>

<div class="content">
    <h1 style = "
    background-color: var(--bg-color-3);
    padding: 2vh;
    margin: 2vh;
    ">
        Welcome to Hexboard 2026
    </h1>

    <p>
        Below are buttons to navigate to different parts of the app. 
    </p>
    <div class="button-menu">
     <a href={resolve('/scouting')} class="button">
            Scouting
        </a>
        <a href={resolve('/member-dash')} class="button-center">  
            Member Dashboard
        </a>
        <a href={resolve('/data-viewer')} class="button-right">
            Data
        </a>
    </div>
    <p>
        The scouting button will lead to a second navigation menu to determine what type of scouting you want to do. 
        <br>
        Member Dashboard leads to an area where you can view your stats, log hours, and other fun activities.
        <br>
        The final button is the data viewer. You can see specific team stats, view tables, compare, and other data analysis tooling. 
        <br>
        There is also an admin panel accessible in the top navbar. More information can be found inside the panel.
    </p>
</div>