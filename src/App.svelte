<script>

</script>

<main>
	<header>
		<h2>Patient Portal</h2>
		<img  src='/images/profile.png' id="Profile">
		<img src='images/logo.png' id ="icon" >
	</header>
	<div id="container">
		<div class="box1">
      <a href="Labs.svelte" target="_blank"><h1>Lab Results</h1></a>
    </div>
		<div class="box2">
      <a href="medication.svelte" target="_blank"><h1>Med Results</h1></a>
    </div>
		<div class="box3">
      
      <a href="Diagnosis.svelte" target="_blank"><h1>Dia Results</h1></a>
    
    </div>
		<span class="stretch"></span>
	  </div>
	<footer>
		<h3>Ehealth</h3>
	</footer>
</main>

<style>

/* Style the header */
header {

  background:linear-gradient(rgba(6, 163, 236, 0.582),rgba(15, 98, 136, 0.356));
  padding: 10px;
  text-align: center;
  font-size: 35px;

}
#icon{
  position: absolute;
  top: 8px;
  left: 16px;
  font-size: 18px;
}
#Profile{
  position: absolute;
  top: 8px;
  right: 16px;
  font-size: 18px;  
}
#container {
  border: 2px #444;
  height: 125px;
  text-align: justify;
  -ms-text-justify: distribute-all-lines;
  text-justify: distribute-all-lines;
  /* just for demo */
  min-width: 612px;
}

.box1,
.box2,
.box3{
  padding: 80px;
  width: 200px;
  height: 200px;
  margin-top: 7%;
  text-align: center;
  vertical-align: top;
  display: inline-block;
  *display: inline;
  zoom: 1
}
#lab {
  width: 300px;
  height: 300px;
  object-fit: cover;
  margin:auto;
  
}

.stretch {
  width: 100%;
  display: inline-block;
  font-size: 0;
  line-height: 0
}

.box1{

  background: #ccc

}
.box3 {
  background: #ccc
}

.box2 {
  background: #0ff
}
footer {
            position: fixed;
            padding: 10px 10px 0px 10px;
            bottom: 0;
            width: 100%;
            /* Height of the footer*/ 
            height: 50px;
			background:linear-gradient(rgba(6, 163, 236, 0.582),rgba(15, 98, 136, 0.356));
			color: white;
			text-align: center;
        }

</style>