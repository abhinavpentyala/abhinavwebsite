<script>
    import Cards from "./cards.svelte"
    
    
    </script>

    <main>
    <h1>Programming Skills</h1>
    <Cards title = "Java" language = "Intermediate" description = "Did lot of problem solving codes, and some projects"></Cards>
    <Cards title = "Javascript" language = "Intermediate" description = "Did many projects, including a library database code, and an authentication page"></Cards>
    <Cards title = "Svelte" language = "Intermediate" description = "Did many projects on svelte, including this website"></Cards>
    <Cards title = "Python" language = "Beginner" description = "Did some basic python while doing django web development"></Cards>
    <Cards title = "Mit App Inventor" language = "Android App" description = "Made many apps that were able to solve daily problems"></Cards>
    </main>
    
    <style>
    main {
    
    }
    h1 {
		text-align:center;
		padding: 1em;
		background-color:#232425;
        justify-content: center;
        color: white;
        margin: 0%;
        font-family: 'IBM Plex Mono', monospace;
    }
    
    </style>