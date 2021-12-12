<script>
	import { Router, Route, Link, link } from "svelte-routing";
	import Home from "./Home.svelte";
	import About from "./About.svelte";
	import Projects from "./Projects.svelte";
	import Skills from "./Skills.svelte";

	export let name;
	export let url = "";
</script>

<Router {url}>
	<nav class="flex-container">
		<div class = "Left"><p class="link"><Link to="/">Abhinav</Link></p></div>
		<div class = "Right">
			<p class="link"><Link to="about">About</Link></p>
			<p class="link"><Link to="projects">Projects</Link></p>
			<p class="link"><Link to="skills">Skills</Link></p>
		</div>
	</nav>
	<Route path="about" component={About} />
	<Route path="/"><Home /></Route>
	<Route path="projects" component={Projects} />
	<Route path="skills" component={Skills} /> 
</Router>

<style>
	nav {
		font-family: 'IBM Plex Mono', monospace;
		font-size: medium;
		background-color: #1c1d1e;
		text-decoration: none;
		color: white;
		height: 3rem;
		flex: 10px;
	}

	.link {
		text-decoration: none;
		color: #a9a9b3;
		margin-left: 1rem;
		margin-right: 1rem;
		margin-top: 1.3rem;
		font-weight: 600;
		font-size: larger;
	}
	.flex-container {
		display: flex;
		justify-content:center;
		align-items: center;
		flex-direction: row;
		/* margin:4rem;	 */

		color: black;
	}

	p {
		margin: 0em;
		margin-bottom: 20px;
	}

	.Left {
		float: left;
		margin-right: 25rem;
	
	}
	.Right {
		float: Right;
		display: flex;
	}

	@media (min-width: 640px) {
		main { 
			max-width: none;
		}
	}
</style>
