<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Boîte de cookies</title>
    <style>
        /* Style CSS pour la boîte de cookies */
        #cookie-container {
            position: fixed;
            bottom: 0;
            left: 0;
            width: 100%;
            padding: 15px;
            background-color: #333;
            color: #fff;
            text-align: center;
            display: none;
        }

        #cookie-container button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <!-- Boîte de cookies -->
    <div id="cookie-container">
        <p>Nous utilisons des cookies pour améliorer votre expérience sur notre site. En continuant, vous acceptez notre utilisation des cookies.</p>
        <button onclick="accepterCookies()">J'accepte</button>
    </div>

    <!-- Votre contenu de page va ici -->

    <script>
        // Fonction pour cacher la boîte de cookies et enregistrer la préférence de l'utilisateur
        function accepterCookies() {
            document.getElementById('cookie-container').style.display = 'none';
            // Vous pouvez ajouter ici du code pour enregistrer la préférence de l'utilisateur, par exemple avec des cookies ou en utilisant une base de données.
        }

        // Vérifier si l'utilisateur a déjà accepté les cookies (par exemple, en consultant un cookie préexistant)
        // Si l'utilisateur n'a pas encore accepté les cookies, afficher la boîte de cookies.
        if (document.cookie.indexOf('cookies_accepted') === -1) {
            document.getElementById('cookie-container').style.display = 'block';
        }
    </script>

</body>
</html>
