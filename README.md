<html>
<head>
<title>Moyenne</title>
</head>
<body>
<h1><a href="https://www.letudiant.fr/college/methodologie-college/article/comment-calculer-une-moyenne.html#:%7E:text=Pour%20calculer%20une%20moyenne%20pond%C3%A9r%C3%A9e,par%20la%20somme%20des%20coefficients">ICI UN SUPER LIEN</a><h1>
 
<h1><u>Bienvenue sur la page de Julien Dupuis</u></h1>

<p>Maths : <input type="text" size="5" id="Maths" maxlength="5"></p> 


<p>Physique : <input type="text" size="5" id="Physique" maxlength="5"></p> 
<p>NSI : <input type="text" size="5" id="NSI" maxlength="5"></p> 

<p> Choisis ton mode :</p>

<p><input type="radio" name="choix" id="les trois"> moyenne des trois</p>
<p><input type="radio" name="choix" id="physique et maths"> physique et maths</p>
<p><input type="radio" name="choix" id="nsi et maths"> nsi et maths</p>
<p><input type="radio" name="choix" id="nsi et physique"> nsi et physique</p>

<input type="button" onclick="Calcul()" value="Calculer"> 

<p>Moyenne : <input type="text" size="10" id="Moyenne" disabled="disabled"></p>

<script> 

function Calcul() { 

  let Maths = Number(document.getElementById("Maths").value); 

  let Physique= Number(document.getElementById("Physique").value); 

  let NSI= Number(document.getElementById("NSI").value); 


  if (document.getElementById("les trois").checked){

    	let MOYENNE = (NSI+Physique+Maths)/3; 

   	document.getElementById("Moyenne").value = MOYENNE; 


  } 
  if (document.getElementById("nsi et maths").checked){

    	let MOYENNE = (NSI+Maths)/2; 

   	document.getElementById("Moyenne").value = MOYENNE; 


  } 
  if (document.getElementById("physique et maths").checked){

    	let MOYENNE = (Physique+Maths)/2; 

   	document.getElementById("Moyenne").value = MOYENNE; 
  }
  if (document.getElementById("nsi et physique").checked){

    	let MOYENNE = (Physique+NSI)/2; 

   	document.getElementById("Moyenne").value = MOYENNE; 
  }

}	 

  
</script>

<hr>
<p><b><u>clique sur cette image afin d'observer un magnifique tutoriel sur le thÃªme des moyennes</u></b></p>
<a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjb0sCo2oSEAxVY_7sIHWPyAKgQtwJ6BAgfEAI&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3Da-RRUlS_CR8&usg=AOvVaw3w6w55mSSBo8DEcvAvmmAu&opi=89978449"><img src="Fractale.jpg"width = 150 lengh= 150></a>

