<MO-DJIB CONSULTING>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mo-Djib Consulting</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        /* Styles pour la navbar */
        .navbar {
            background-color: transparent;
            padding: 20px 0;
        }

        .navbar-brand {
            color: #007bff;
            font-weight: bold;
            font-size: 32px;
        }

        .navbar-nav .nav-item .nav-link {
            color: #343a40;
            font-weight: bold;
            font-size: 18px;
            padding: 10px 20px;
            transition: all 0.3s ease;
        }

        .navbar-nav .nav-item .nav-link:hover {
            background-color: #007bff;
            color: #fff;
            border-radius: 10px;
        }

        /* Styles pour les sections */
        .section {
            padding: 50px 0;
            background-color: #f8f9fa;
        }

        .section-title {
            font-weight: bold;
            font-size: 24px;
            color: #343a40;
            margin-bottom: 20px;
        }

        .rectangle {
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
        }

        .rectangle:hover {
            transform: scale(1.05);
            box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.2);
        }

        .rectangle h2 {
            color: #007bff;
            font-weight: bold;
            font-size: 24px;
            margin-bottom: 15px;
        }

        .rectangle p {
            color: #6c757d;
            font-size: 18px;
        }

        .icon {
            font-size: 36px;
            margin-right: 10px;
            color: #007bff;
        }

        /* Styles pour les images */
        .section-image {
            width: 100%;
            height: auto;
            border-radius: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        /* Animation d'agrandissement des images au survol */
        .section-image:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-light">
    <div class="container-fluid">
        <a class="navbar-brand" href="#">Mo-Djib Consulting</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#">ACCUEIL</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">FORMATIONS</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">AUDIT</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">ACCOMPAGNEMENT</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">E-PACK HYGIÈNE</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">ACTUALITÉS</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">CONTACTEZ-NOUS</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<!-- Grande image -->
<section class="big-image">
    <img src="1620768752769.jpg" class="section-image" alt="Image">
</section>

<!-- Titre Bienvenue -->
<section class="welcome-message section">
    <div class="container">
        <div class="row">
            <div class="col-md-12 text-center">
                <h1 class="gold-text">Bienvenue chez Mo-Djib Consulting</h1>
                <p>Votre partenaire mondial pour la qualité, l'hygiène et la sécurité alimentaire</p>
            </div>
        </div>
    </div>
</section>

<!-- Section avec texte et image -->
<section class="about-section section">
    <div class="container">
        <div class="row">
            <div class="col-md-6">
                <div class="rectangle">
                    <h2>Plus de 1 ans d’expériences</h2>
                    <p>Votre expert en qualité, hygiène et sécurité des aliments</p>
                    <p>MO-DJIB CONSULTING est un cabinet de conseil, d’audit et de formation dans le domaine de la qualité, l’hygiène et la sécurité des denrées alimentaires. Notre équipe vous accompagne : porteurs de projets et chefs d’entreprise quelque soit votre type d’activité : du snack à l’industrie agro-alimentaire, en passant par la restauration commerciale, collective, la distribution et les métiers de bouche (boulangerie, patisserie, boucherie, charcuterie,..)</p>
                </div>
            </div>
            <div class="col-md-6">
                <img src="1697909151559 (1).jpg" class="section-image" alt="Image">
            </div>
        </div>
    </div>
</section>

<!-- Section Nos Services -->
<section class="our-services section">
    <div class="container">
        <div class="row">
            <div class="col-md-6">
                <div class="rectangle">
                    <h2>Nos Services</h2>
                    <p>Nous sommes à votre écoute</p>
                </div>
            </div>
            <div class="col-md-6">
                <div class="row">
                    <div class="col-md-4">
                        <div class="rectangle">
                            <i class="icon fas fa-chalkboard-teacher"></i>
                            <h3>Former</h3>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="rectangle">
                            <i class="icon fas fa-clipboard-check"></i>
                            <h3>Auditer</h3>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="rectangle">
                            <i class="icon fas fa-handshake"></i>
                            <h3>Accompagner</h3>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Section Qui sommes-nous -->
<section class="who-we-are section">
    <div class="container">
        <div class="row">
            <div class="col-md-6">
                <div class="rectangle">
                    <h2>Qui sommes-nous ?</h2>
                    <p>MO-DJIB CONSULTING, les experts dont vous avez besoin</p>
                    <p>Notre expérience professionnelle nous permet de vous apporter les meilleurs conseils et expertises en sécurité alimentaire quelque soit votre projet ou votre activité.</p>
                    <ul>
                        <li>Maîtrise de la réglementation en vigueur</li>
                        <li>Mise en place des process</li>
                        <li>Accompagnement des équipes</li>
                    </ul>
                </div>
            </div>
            <div class="col-md-6">
                <img src="1710097249066.jpg" class="section-image" alt="Image">
            </div>
        </div>
    </div>
</section>

<!-- Section Notre Pack Hygiène -->
<section class="pack-hygiene section">
    <div class="container">
        <div class="row">
            <div class="col-md-12">
                <div class="rectangle">
                    <h2>Notre Pack Hygiène</h2>
                    <p>Inspection d'hygiène, formation HACCP, audit et accompagnement</p>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Section Nos Services -->
<section class="our-services section">
    <div class="container">
        <div class="row">
            <div class="col-md-4">
                <div class="rectangle">
                    <h3>Formations</h3>
                    <p>MO-DJIB CONSULTING vous propose des formations en hygiène alimentaire spécifiques selon le type d’activité; restauration commerciale, collective, petite enfance, …une formation bonnes pratiques d’hygiène, et des formations HACCP et ISO22000 destinées aux industries agro-alimentaires.</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="rectangle">
                    <h3>Audits</h3>
                    <p>Dans le cadre du système de vérification du plan HACCP, le Cabinet MO-DJIB CONSULTING peut vous accompagner sur l’année grâce à des audits réguliers ou de façon ponctuelle avec suivi des actions correctives incluant le suivi des analyses bactériologiques. Faites nous confiance afin d’être prêt en cas de visite par les services officiels de l’état. En fonction de vos objectifs, notre équipe d’experts vous accompagne. Contactez-nous !</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="rectangle">
                    <h3>Accompagnement</h3>
                    <p>Bonnes Pratiques d’Hygiène, Plan HACCP, traçabilité et Gestion des produits non conformes… Comptez sur nous pour vous accompagner pour votre dossier plan de maîtrise sanitaire, ou dossier d’agrément sanitaire, votre SMSDA ou votre DUERP. Nous pouvons également vous proposer une solution numérique pour la digitalisation de vos auto-contrôles réglementaires avec sondes connectées.</p>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Section Contactez-nous -->
<section class="contact-us section">
    <div class="container">
        <div class="row">
            <div class="col-md-12">
                <div class="rectangle">
                    <h2>Contactez-nous</h2>
                    <p>Vous souhaitez en savoir plus sur nos services ou discuter de vos besoins spécifiques en matière de qualité, d'hygiène et de sécurité alimentaire ? N'hésitez pas à nous contacter dès aujourd'hui. Notre équipe est là pour répondre à toutes vos questions et vous aider à atteindre vos objectifs. Chez Mo-Djib Consulting, votre succès est notre priorité.</p>
                    <p>© 2024 Mo-Djib Consulting. Tous droits réservés.</p>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Bootstrap Scripts -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>
</html>
