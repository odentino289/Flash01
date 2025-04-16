<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site Flash - Ton site pro en 48h</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; color: #333; }
        header { background: #fff; padding: 20px; text-align: center; }
        header h1 { margin: 0; font-size: 2em; }
        main { padding: 20px; }
        .button { background: #ff6600; color: #fff; border: none; padding: 15px 25px; font-size: 1em; cursor: pointer; text-decoration: none; }
        .section { margin-bottom: 40px; }
        .flex { display: flex; gap: 20px; flex-wrap: wrap; }
        .card { border: 1px solid #ddd; padding: 20px; flex: 1; min-width: 250px; }
        form input, form textarea { width: 100%; padding: 10px; margin: 5px 0; }
        form button { background: #333; color: #fff; padding: 15px; border: none; cursor: pointer; }
    </style>
</head>
<body>

<header>
    <h1>SITE FLASH</h1>
    <p>Ton site pro en 48h</p>
    <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=dentiomar" class="button">Commander via PayPal</a>
</header>

<main>
    <section class="section">
        <h2>Je crée un site professionnel en 48h seulement</h2>
        <p>Idéal pour obtenir plus de clients et crédibiliser ton activité.</p>
        <div class="flex">
            <div class="card">
                <h3>Site vitrine</h3>
                <p>Une page professionnelle pour présenter ton activité.</p>
            </div>
            <div class="card">
                <h3>Tunnel de vente</h3>
                <p>Une page de capture + page de vente pour vendre ton offre.</p>
            </div>
        </div>
    </section>

    <section class="section">
        <h2>À propos de moi</h2>
        <div class="flex">
            <div class="card">
                <img src="https://via.placeholder.com/150" alt="Portrait d'Omar" style="border-radius: 50%;">
            </div>
            <div class="card">
                <p>Moi c'est Omar, et je suis spécialisé dans la création de sites à forte valeur ajoutée.</p>
            </div>
        </div>
    </section>

    <section class="section">
        <h2>Portfolio</h2>
        <div class="card">
            <p>MON SITE PRO - Ma proposition de valeur</p>
            <!-- Ajoute ici de vrais visuels ou captures d'écran -->
        </div>
    </section>

    <section class="section">
        <h2>Contact</h2>
        <form action="mailto:omardenti35@gmail.com" method="post" enctype="text/plain">
            <input type="text" name="Nom" placeholder="Nom" required>
            <input type="email" name="Email" placeholder="Email" required>
            <textarea name="Message" placeholder="Message" rows="5" required></textarea>
            <button type="submit">Envoyer</button>
        </form>
    </section>
</main>

</body>
</html>
