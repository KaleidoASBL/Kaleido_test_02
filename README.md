<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Kaleido - Un catalyseur culturel dédié à promouvoir la diversité artistique et l'inclusion sociale.">
    <title>Kaleido ASBL</title>
    <style>
        body { font-family: 'Arial', sans-serif; margin: 0; padding: 0; line-height: 1.6; }
        header { background: #333; color: #fff; padding: 10px 0; text-align: center; }
        header h1 { margin: 0; }
        .container { width: 80%; margin: 0 auto; padding: 20px; }
        .section { padding: 40px 0; }
        .title { font-size: 32px; color: #333; text-align: center; }
        .subtitle { font-size: 24px; color: #555; text-align: center; }
        .text { font-size: 16px; color: #666; }
        .btn { display: inline-block; background-color: #0056b3; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px; margin: 10px; }
        .btn:hover { background-color: #004999; }
        .hero { background-color: #f4f4f4; padding: 60px 20px; text-align: center; }
        .section-bg { background-color: #f9f9f9; }
        .card { border: 1px solid #ddd; border-radius: 8px; padding: 20px; margin-bottom: 20px; }
        footer { background: #333; color: #fff; text-align: center; padding: 20px; }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Kaleido ASBL</h1>
        <p>Promouvoir la diversité artistique et l'inclusion sociale</p>
    </header>

    <!-- Page d'Accueil -->
    <div class="hero">
        <h1 class="title">Un Monde Relié par l'Art et la Diversité Culturelle</h1>
        <p class="text">Kaleido - Catalyseur culturel dédié à la promotion de la diversité artistique et de l'inclusion sociale.</p>
    </div>

    <!-- À propos de nous -->
    <div class="section container">
        <h2 class="title">À Propos de Nous</h2>
        <p class="text">Kaleido est une association sans but lucratif (ASBL) dédiée à promouvoir la diversité culturelle et l'inclusion sociale à travers des initiatives artistiques innovantes. Créée pour bâtir des ponts entre les cultures et rendre l’art accessible à tous, Kaleido se positionne comme un incubateur culturel unique, soutenant les talents émergents et les collectifs artistiques de tous horizons.</p>
        <p class="text">Fondée sur les principes de diversité et d’inclusion, l’association Kaleido vise à transformer l'art en un vecteur de dialogue et de cohésion sociale. En créant des opportunités pour les artistes souvent exclus des circuits traditionnels, nous redessinons le paysage culturel pour qu'il devienne un espace où chaque voix, peu importe son origine, puisse s’épanouir pleinement.</p>
    </div>

    <!-- Mission et Vision -->
    <div class="section section-bg container">
        <h2 class="title">Mission et Vision</h2>
        <h3 class="subtitle">Notre Vision</h3>
        <p class="text">Notre vision est celle d’un monde interconnecté par les arts, où la diversité culturelle est valorisée et où chaque individu a accès aux outils de création et d'expression artistique.</p>
        <h3 class="subtitle">Notre Mission</h3>
        <p class="text">Nous nous engageons à réduire les inégalités d'accès à la culture en accompagnant les artistes de toutes origines et en facilitant la co-création pour créer un impact social mesurable.</p>
    </div>

    <!-- Projets -->
    <div id="projects" class="section container">
        <h2 class="title">Nos Projets</h2>
        <div class="card">
            <h3 class="subtitle">KaleidoLab - Incubateur Culturel</h3>
            <p class="text">Accompagnement personnalisé pour les artistes émergents, incluant mentorat, développement de compétences et réseautage international.</p>
        </div>
        <div class="card">
            <h3 class="subtitle">Kaleido Art Festival</h3>
            <p class="text">Un événement annuel célébrant la diversité artistique avec des performances, des expositions, et des ateliers créatifs pour rapprocher les cultures.</p>
        </div>
        <div class="card">
            <h3 class="subtitle">Projets de Co-Création</h3>
            <p class="text">Initiatives collaboratives réunissant des artistes locaux et internationaux pour explorer des thématiques de l'inclusion et de l'innovation sociale.</p>
        </div>
    </div>

    <!-- Rejoignez-nous -->
    <div class="section section-bg container">
        <h2 class="title">Rejoignez-nous</h2>
        <p class="text">Rejoindre Kaleido, c’est soutenir un mouvement dédié à la diversité et à l’inclusion par l’art. Que vous soyez artiste, bénévole, mécène ou entreprise, votre engagement est essentiel.</p>
        <a href="#contact" class="btn">Devenir membre</a>
        <a href="#contact" class="btn">Faire un don</a>
    </div>

    <!-- Contact -->
    <div id="contact" class="section container">
        <h2 class="title">Restons en Contact</h2>
        <p class="text">Vous souhaitez en savoir plus sur Kaleido, collaborer sur un projet artistique, ou simplement échanger avec nous ? Remplissez le formulaire ci-dessous !</p>
        <form>
            <label>Nom :</label><br>
            <input type="text" name="name" required><br>
            <label>Email :</label><br>
            <input type="email" name="email" required><br>
            <label>Message :</label><br>
            <textarea name="message" rows="4" required></textarea><br>
            <button type="submit" class="btn">Envoyer</button>
        </form>
    </div>

    <!-- Footer -->
    <footer>
        <p>Kaleido ASBL | contact@kaleido.org | © 2024 Kaleido</p>
    </footer>

</body>
</html>
