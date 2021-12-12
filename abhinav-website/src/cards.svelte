<script>
export let title;
export let description;
export let language;

</script>
<main><div class="card">
  <div class="container"> 
    <h4><b>{title} | {language}</b></h4>
    <p>{description}</p>
  </div>
  </div>
</main>
  
  
  
  
  <style>
 main {
		text-align:center;
		padding: 1em;
		background-color:#232425;
        justify-content: center;
      
	}

  h1 {
		text-align:center;
		padding: 1em;
		background-color:#232425;
    justify-content: center;
  }
.card {
    font-size:medium;
    text-align: center;
    color:white;
    background-color:#1e1f20;
  box-shadow: 0 10px 12px 0 rgba(0,0,0,0.2);
  transition: 0.5s;
  width: 50%;
  margin: 10px auto;
  font-family: "Montserrat", sans-serif;
  
}


.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}


.container {
  padding: 2px 16px;
}



img{
    width:49.252 px;
    height:49.252 px;
}
</style>

