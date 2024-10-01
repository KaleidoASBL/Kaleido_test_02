<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Kaleido - Un catalyseur culturel dédié à promouvoir la diversité artistique et l'inclusion sociale">
    <title>Kaleido ASBL</title>
    <style>
        body { font-family: 'Arial', sans-serif; margin: 0; padding: 0; line-height: 1.6; }
        .container { width: 80%; margin: 0 auto; padding: 20px; }
        .section { padding: 40px 0; }
        .title { font-size: 32px; color: #333; }
        .subtitle { font-size: 24px; color: #555; }
        .text { font-size: 16px; color: #666; }
        .btn { background-color: #0056b3; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px; }
        .btn:hover { background-color: #004999; }
        .hero { background-color: #f4f4f4; padding: 60px 20px; text-align: center; }
        .section-bg { background-color: #f9f9f9; }
        .card { border: 1px solid #ddd; border-radius: 8px; padding: 20px; margin-bottom: 20px; }
    </style>
</head>
<body>
    <!-- Page d'accueil -->
    <div class="hero">
        <h1 class="title">Kaleido - Un Monde Relié par l'Art</h1>
        <p class="text">Catalyseur culturel dédié à la promotion de la diversité artistique et de l'inclusion sociale.</p>
        <a href="#projects" class="btn">Découvrez nos projets</a>
    </div>

    <!-- À propos de nous -->
    <div class="section container">
        <h2 class="title">À propos de nous</h2>
        <p class="text">Kaleido est une association sans but lucratif dédiée à promouvoir la diversité culturelle et l'inclusion sociale à travers des initiatives artistiques. En tant qu'incubateur culturel, nous soutenons les talents émergents et bâtissons des ponts entre les cultures grâce à des projets innovants qui valorisent la diversité et l'expression artistique.</p>
    </div>

    <!-- Mission et Vision -->
    <div class="section section-bg container">
        <h2 class="title">Mission et Vision</h2>
        <h3 class="subtitle">Notre Vision</h3>
        <p class="text">Un monde où la diversité artistique et culturelle est célébrée, et où chaque voix a la possibilité de s'exprimer et de contribuer à un avenir plus inclusif.</p>
        <h3 class="subtitle">Notre Mission</h3>
        <p class="text">Nous nous engageons à réduire les inégalités d'accès à la culture en accompagnant les artistes de toutes origines et en facilitant la co-création pour créer un impact social mesurable.</p>
    </div>

    <!-- Projets -->
    <div id="projects" class="section container">
        <h2 class="title">Nos Projets</h2>
        <!-- Projet 1 -->
        <div class="card">
            <h3 class="subtitle">KaleidoLab - Incubateur Culturel</h3>
            <p class="text">Accompagnement personnalisé pour les artistes émergents, incluant mentorat, développement de compétences et réseautage international.</p>
        </div>
        <!-- Projet 2 -->
        <div class="card">
            <h3 class="subtitle">Kaleido Art Festival</h3>
            <p class="text">Un événement annuel célébrant la diversité artistique avec des performances, des expositions, et des ateliers créatifs pour rapprocher les cultures.</p>
        </div>
        <!-- Projet 3 -->
        <div class="card">
            <h3 class="subtitle">Projets de Co-Création</h3>
            <p class="text">Initiatives collaboratives réunissant des artistes locaux et internationaux pour explorer des thématiques de l'inclusion et de l'innovation sociale.</p>
        </div>
    </div>

    <!-- Rejoignez-nous -->
    <div class="section section-bg container">
        <h2 class="title">Rejoignez-nous</h2>
        <p class="text">Rejoindre Kaleido, c’est soutenir un mouvement dédié à la diversité et à l’inclusion par l’art. Que vous soyez artiste, bénévole, mécène ou entreprise, votre engagement est essentiel pour bâtir un futur où chaque voix artistique a le pouvoir de se faire entendre.</p>
        <a href="#contact" class="btn">Devenir membre</a>
    </div>

    <!-- Contact -->
    <div id="contact" class="section container">
        <h2 class="title">Contactez-nous</h2>
        <p class="text">Vous souhaitez en savoir plus sur Kaleido, collaborer sur un projet artistique, ou simplement échanger avec nous ? Remplissez le formulaire ci-dessous ou envoyez-nous un message !</p>
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
</body>
</html>
