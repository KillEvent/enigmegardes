<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Énigme Résolue</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
            background-color: #f4f4f4;
        }
        .container {
            display: none;
            background-color: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Bravo!</h1>
        <p>Vous avez déchiffré l'énigme! Les gardes, impressionnés par votre perspicacité, vous ont laissé entrer.</p>
        <p>Vous pouvez maintenant participer à la murder party. Préparez-vous à interroger les autres suspects et à dévoiler le mystère!</p>
    </div>

    <script>
        var motDePasse = prompt("Entrez le mot de passe à 4 chiffres:");
        if (motDePasse === "1234") { // Remplacez "1234" par votre mot de passe
            document.querySelector('.container').style.display = 'block';
        } else {
            alert("Mot de passe incorrect!");
        }
    </script>
</body>
</html>
