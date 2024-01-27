<html>

<head>
  <meta charset="UTF-8">
  <title>calculatrice</title>

</head>

<body>
<script>
function Calcul() {
  let premier = Number(document.getElementById("1er").value);
  let deuxieme= Number(document.getElementById("2eme").value);
  if (document.getElementById("diviser").checked) {
    	let NomB = premier/deuxieme;
   	document.getElementById("resultat").value = NomB;
  }
  if (document.getElementById("multiplier").checked) {
    	let NB = premier*deuxieme;
    	document.getElementById("resultat").value = NB;

  }
}	


</script>
<h3>Calculatrice en ligne</h3>
<p>premier : <input type="text" size="5" id="1er" maxlength="5"></p>
<p>deuxieme : <input type="text" size="5" id="2eme" maxlength="5"></p>

<p>Choisir le mode :
    <input type="radio" name="choix" id="diviser"> diviser(1erpar 2eme)
    <input type="radio" name="choix" id="multiplier"> multiplier
    <input type="button" onclick="Calcul()" value="Calculer">
</p>
<p>Résultat : <input type="text" size="10" id="resultat" disabled="disabled"></p>







</body>



</html>
