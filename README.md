<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bienvenue chez Mo-Djib Consulting</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background: url('https://gist.github.com/assets/168087487/d3dbfa90-80de-466a-8d53-eba7f79cf573') no-repeat center center fixed;
            background-size: cover;
            background-color: rgba(0, 0, 0, 0.5);
            background-blend-mode: darken;
        }

        header {
            background: linear-gradient(to right, #3a6186, #89253e);
            color: white;
            padding: 20px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            z-index: 1000;
        }

        header img.logo {
            height: 80px; /* Taille du logo */
            margin-right: 20px;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: flex-end;
        }

        nav ul li {
            position: relative;
        }

        nav ul li a {
            display: block;
            color: white;
            text-decoration: none;
            padding: 15px 20px;
            transition: background-color 0.3s ease;
        }

        nav ul li a:hover {
            background-color: #555;
        }

        nav ul li ul {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            background-color: #444;
            padding: 0;
        }

        nav ul li:hover ul {
            display: block;
            animation: fadeIn 0.3s;
        }

        nav ul li ul li {
            width: 200px;
        }

        section {
            padding: 120px 20px 20px; /* Espace ajouté en haut pour éviter l'overlap avec le header */
            max-width: 1200px;
            margin: auto;
            background-color: rgba(255, 255, 255, 0.9);
            text-align: center;
            animation: fadeIn 1s;
        }

        section h1 {
            font-size: 3rem;
            color: #333;
            margin-bottom: 20px;
        }

        section p {
            font-size: 1.2rem;
            color: #555;
            margin-bottom: 30px;
        }

        .transparent-rectangle {
            background-color: rgba(255, 255, 255, 0.8);
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
            transition: transform 0.5s ease;
        }

        .transparent-rectangle:hover {
            transform: scale(1.05);
        }

        .transparent-rectangle h3 {
            font-size: 1.5rem;
            color: #333;
            margin-bottom: 20px;
        }

        .transparent-rectangle p {
            font-size: 1.1rem;
            color: #555;
            margin-bottom: 20px;
        }

        .contact-info {
            text-align: center;
            margin-top: 30px;
        }

        .contact-info a {
            background-color: #25d366;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1.1rem;
            margin-right: 20px;
        }

        .contact-info span {
            font-size: 1.1rem;
            color: #555;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }

            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>

<body>
    <header>
        <img src="https://gist.github.com/assets/168087487/3937ec2f-36a3-4158-8638-f5a49547f06c" alt="Logo Mo-Djib Consulting" class="logo">
        <nav>
            <ul>
                <li><a href="#"><i class="fas fa-home"></i> Accueil</a></li>
                <li><a href="#"><i class="fas fa-concierge-bell"></i> Nos Services</a>
                    <ul>
                        <li><a href="#"><i class="fas fa-user-graduate"></i> Former</a></li>
                        <li><a href="#"><i class="fas fa-clipboard-check"></i> Auditer</a></li>
                        <li><a href="#"><i class="fas fa-handshake"></i> Accompagner</a></li>
                    </ul>
                </li>
                <li><a href="#"><i class="fas fa-info-circle"></i> Qui sommes-nous ?</a></li>
                <li><a href="#"><i class="fas fa-box"></i> Notre Pack Hygiène</a></li>
                <li><a href="#"><i class="fas fa-newspaper"></i> Actualités</a></li>
                <li><a href="#"><i class="fas fa-handshake"></i> Partenaires</a></li>
                <li><a href="#"><i class="fas fa-envelope"></i>
Contactez-nous</a></li>
</ul>
</nav>
</header>
<section>
<h1>Bienvenue chez Mo-Djib Consulting</h1>
<p>Votre partenaire mondial pour la qualité, l'hygiène et la sécurité alimentaire</p>
<div class="transparent-rectangle">
<h3>Plus de 1 an d’expériences</h3>
<p>Votre expert en qualité, hygiène et sécurité des aliments</p>
<p>MO-DJIB CONSULTING est un cabinet de conseil, d’audit et de formation dans le domaine de la qualité, l’hygiène et la sécurité des denrées alimentaires. Notre équipe vous accompagne : porteurs de projets et chefs d’entreprise quel que soit votre type d’activité : du snack à l’industrie agro-alimentaire, en passant par la restauration commerciale, collective, la distribution et les métiers de bouche (boulangerie, pâtisserie,boucherie, charcuterie, etc.)</p>
<div class="contact-info">
<span>Prendre RDV:</span>
<a href="https://wa.me/message/WZHC7CEMDMMXL1"><i class="fab fa-whatsapp"></i> WhatsApp</a>
<span>+253 77 01 70 37</span>
</div>
</div>
<h2>Nos Services</h2>
<p>Nous sommes à votre écoute</p>
<div class="service-list">
<div class="service-item">
<h3>Former</h3>
<p>Formations spécifiques en hygiène alimentaire selon votre activité.</p>
</div>
<div class="service-item">
<h3>Auditer</h3>
<p>Audits réguliers ou ponctuels pour vérifier votre plan HACCP.</p>
</div>
<div class="service-item">
<h3>Accompagner</h3>
<p>Accompagnement pour la mise en place de plans et processus hygiéniques.</p>
</div>
</div>
<h2>Qui sommes-nous ?</h2>
<p>MO-DJIB CONSULTING, les experts dont vous avez besoin</p>
<p>Notre expérience professionnelle nous permet de vous apporter les meilleurs conseils et expertises en sécurité alimentaire quel que soit votre projet ou votre activité.</p>
<ul>
<li>Maîtrise de la réglementation en vigueur</li>
<li>Mise en place de process</li>
<li>Accompagnement des équipes</li>
</ul>
<img src="images/equipe.jpg" alt="Image de notre équipe">
<h2>Notre Pack Hygiène</h2>
<p>Inspection d'hygiène, formation HACCP, audit et accompagnement</p>
<h3>Formations</h3>
<p>MO-DJIB CONSULTING vous propose des formations en hygiène alimentaire spécifiques selon le type d’activité; restauration commerciale, collective, petite enfance, … une formation bonnes pratiques d’hygiène, et des formations HACCP et ISO22000 destinées aux industries agro-alimentaires.</p>
<h3>Audits</h3>
<p>Dans le cadre du système de vérification du plan HACCP, le Cabinet MO-DJIB CONSULTING peut vous accompagner sur l’année grâce à des audits réguliers ou de façon ponctuelle avec suivi des actions correctives incluant le suivi des analyses bactériologiques. Faites-nous confiance afin d’être prêt en cas de visite par les services officiels de l’état. En fonction de vos objectifs, notre équipe d’experts vous accompagne. Contactez-nous !</p>
<h3>Accompagnement</h3>
<p>Bonnes Pratiques d’Hygiène, Plan HACCP, traçabilité et Gestion des produits non conformes… Comptez sur nous pour vous accompagner pour votre dossier plan de maîtrise sanitaire, ou dossier d’agrément sanitaire, votre SMSDA ou votre DUERP. Nous pouvons également vous proposer une solution numérique pour la digitalisation de vos auto-contrôles réglementaires avec sondes connectées.</p>
<h2>Contactez-nous</h2>
<p>Vous souhaitez en savoir plus sur nos services ou discuter de vos besoins spécifiques en matière de qualité, d'hygiène et de sécurité alimentaire ? N'hésitez pas à nous contacter dès aujourd'hui. Notre équipe est là pour répondre à toutes vos questions et vous aider à atteindre vos objectifs. Chez Mo-Djib Consulting, votre succès est notre priorité.</p>
</section>
<footer>
© 2024 Mo-Djib Consulting. Tous droits réservés.
</footer>

</body>
</html>
