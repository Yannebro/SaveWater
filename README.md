<!DOCTYPE html><html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eau Propre pour Tous</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #fef9f2;
            color: #333;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 2rem;
            background-color: #fff;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        nav a {
            margin-left: 1rem;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        .hero {
            display: flex;
            flex-direction: row;
            align-items: center;
            justify-content: space-between;
            padding: 3rem 2rem;
            background-color: #fff7ec;
        }
        .hero img {
            max-width: 45%;
            border-radius: 8px;
        }
        .hero-text {
            max-width: 50%;
        }
        .hero-text h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        .donate-button {
            padding: 1rem 2rem;
            background-color: #f04e23;
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 1.2rem;
            cursor: pointer;
            margin-top: 1rem;
        }
        section {
            padding: 2rem;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 1rem;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <div><strong>Eau Propre pour Tous</strong></div>
        <nav>
            <a href="index.html">Accueil</a>
            <a href="apropos.html">À propos</a>
            <a href="projets.html">Nos projets</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header><section class="hero">
    <div class="hero-text">
        <h1>Combattre la consommation d’eaux sales dans les milieux défavorisés</h1>
        <p>Rejoignez-nous pour offrir une eau propre et sauver des vies. Votre don peut tout changer.</p>
        <button class="donate-button" onclick="window.location.href='https://don.eaupropre.org'">Faire un don</button>
    </div>
    <img src="https://via.placeholder.com/400x400" alt="Enfant buvant de l'eau propre">
</section>

<footer>
    &copy; 2025 Eau Propre pour Tous. Tous droits réservés.
</footer>

</body>
</html>
