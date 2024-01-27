<html>

<head>
  <meta charset="UTF-8">
  <title>Convertisseur</title>

</head>

<body onload="init()">
<script>
function init() {
  document.getElementById("date").innerHTML = Date();
}

function Calcul() {
  entier = Number(document.getElementById("entier").value);
  if (document.getElementById("Wh").checked) {
    	let Wh = entier*3600;
   	document.getElementById("resultat").value = Wh;
  }
  if (document.getElementById("J").checked) {
    	let J = entier/3600;
    	document.getElementById("resultat").value = J;

  }
}	
</script>

  <p id="date"></p>

  <h3>Convertir un entier en binaire et en hexadécimal</h3>

  <p>Entier à convertir : <input type="text" size="5" id="entier" maxlength="5"></p>

  <p>Cette page permet de convertir les Wh en J.</p>

  <p>choisir ton unité :
    <input type="radio" name="choix" id="Wh"> Wh
    <input type="radio" name="choix" id="J"> Joul
    <input type="button" onclick="Calcul()" value="Convertir">
  </p>

  <p>Résultat : <input type="text" size="10" id="resultat" disabled="disabled"></p>

</body>

</html>
