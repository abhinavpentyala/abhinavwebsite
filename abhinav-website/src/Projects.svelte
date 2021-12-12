<script>
import Cards from "./cards.svelte"


</script>
<main>
<h1>Projects</h1>
<Cards title = "Grade Calculator" language = "Java" description = "This Program allows you to simply enter any grade in percentage, and it will give you a letter grade for it (eg A, B)"></Cards>
<Cards title = "Tic Tac Toe" language = "Svelte" description = "This Program allows you to play tic tac toe against a friend!"></Cards>
<Cards title = "Number Guessing" language = "Java" description = "This Program allows you to play a fun Number Guessing game. The user must guess a number from 1-100. Every wrong guess gets them a hint. The goal is to get the number in the least turns. "></Cards>
<Cards title = "Calculator" language = "Android App" description = "This Program allows you to get a simple calculator that can be used on android."></Cards>
<Cards title = "Problem Solving" language = "Java" description = "Found solutions to various problems such as checking if a number was a palindrome, using sorting algorithms to arrange numbers and letters in a sequence."></Cards>
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