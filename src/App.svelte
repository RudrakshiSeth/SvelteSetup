<script>

</script>

<main>
	<header>
		<h2>Patient Portal</h2>
		<img  src='/images/profile.png' id="Profile">
		<img src='images/logo.png' id ="icon" >
	</header>
	<div id="container">
		<div class="lab">
      <a href="Labs.svelte" target="_blank"><h1>Lab Results</h1></a>
    </div>
		<div class="med">
      <a href="medication.svelte" target="_blank"><h1>Med Results</h1></a>
    </div>
		<div class="dia">
      
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

.lab,
.med,
.dia{
  padding: 80px;
  width: 200px;
  height: 200px;
  margin-top: 7%;
  text-align: center;
  vertical-align: top;
  display: inline-block;
  *display: inline;
  zoom: 1;
  background-size:     cover;      
  background-repeat:   no-repeat;
  background-position: center center;   
}

.stretch {
  width: 100%;
  display: inline-block;
  font-size: 0;
  line-height: 0
}

.lab{

  background-image:linear-gradient(rgba(255,255,255,0.4), rgba(255,255,255,0.4)),url('/images/lab.jpeg');
}
.dia {
  background-image:linear-gradient(rgba(255,255,255,0.4), rgba(255,255,255,0.4)),url('/images/diagnosis.jpeg');
}

.med {
  background-image:linear-gradient(rgba(255,255,255,0.4), rgba(255,255,255,0.4)),url('/images/med.jpeg');
}
footer {
            position: fixed;
            padding: 10px 10px 0px 10px;
            bottom: 0;
            width: 100%;
          
            height: 50px;
			background:linear-gradient(rgba(6, 163, 236, 0.582),rgba(15, 98, 136, 0.356));
			color: white;
			text-align: center;
        }

</style>