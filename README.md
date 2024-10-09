<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Lavage Auto - Service de Qualité</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #007BFF;
            color: white;
            padding: 20px;
            text-align: center;
        }
        h1 {
            margin: 0;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .services {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }
        .service-item {
            background-color: white;
            padding: 20px;
            width: 30%;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        footer {
            background-color: #007BFF;
            color: white;
            text-align: center;
            padding: 10px;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
        form {
            background-color: white;
            padding: 20px;
            margin-top: 20px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            max-width: 400px;
            margin: 20px auto;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        button {
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <header>
        <h1>Lavage Auto Professionnel</h1>
        <p>Des services de qualité pour un véhicule toujours impeccable</p>
    </header>

    <section>
        <h2>Nos Services</h2>
        <div class="services">
            <div class="service-item">
                <h3>Lavage extérieur</h3>
                <p>Un lavage complet pour redonner de l’éclat à votre voiture.</p>
            </div>
            <div class="service-item">
                <h3>Lavage intérieur</h3>
                <p>Nettoyage en profondeur de l’habitacle, des sièges et des tapis.</p>
            </div>
            <div class="service-item">
                <h3>Polissage</h3>
                <p>Ravivez la peinture de votre voiture avec notre service de polissage professionnel.</p>
            </div>
        </div>
    </section>

    <section>
        <h2>Contactez-nous</h2>
        <form>
            <input type="text" placeholder="Nom" required>
            <input type="email" placeholder="Email" required>
            <textarea placeholder="Votre message" rows="5" required></textarea>
            <button type="submit">Envoyer</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Lavage Auto. Tous droits réservés.</p>
    </footer>

</body>
</html>
