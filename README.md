<MO-DJIB CONSULTING>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mo-Djib Consulting</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        /* Navbar Styles */
        .navbar {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            z-index: 1000;
            background-color: #1B1B1B;
            border-radius: 0;
            box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.1);
        }
        .navbar-brand {
            color: #fff;
            font-size: 24px;
            font-weight: bold;
        }
        .navbar-nav .nav-link {
            color: #fff;
            transition: color 0.3s;
            font-size: 16px;
            font-weight: 500;
            margin-right: 20px;
        }
        .navbar-nav .nav-link:hover {
            color: #FFA500;
        }
        /* Body padding to compensate for fixed navbar */
        body {
            padding-top: 70px;
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #F8F9FA;
            color: #000000; /* Couleur noire par défaut */
        }
        /* Banner */
        .banner {
            background-image: url('https://images.unsplash.com/photo-1590252503894-e95a08e24736');
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #fff;
            text-align: center;
            margin-bottom: 50px;
        }
        .banner h1 {
            font-size: 48px;
            margin-bottom: 20px;
        }
        .banner p {
            font-size: 20px;
        }
        /* Services Section */
        .services {
            padding: 50px 0;
            background-color: #fff;
        }
        .service-item {
            margin-bottom: 40px;
            text-align: center;
        }
        .service-item h3 {
            font-size: 24px;
            margin-bottom: 20px;
        }
        .service-item p {
            font-size: 16px;
            color: #6C757D;
        }
        /* Contact Section */
        .contact {
            background-color: #1B1B1B;
            color: #fff;
            padding: 50px 0;
        }
        .contact h2 {
            font-size: 36px;
            margin-bottom: 30px;
        }
        .contact p {
            font-size: 18px;
            margin-bottom: 30px;
        }
        /* Footer */
        footer {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
        }
    </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg">
    <div class="container">
        <a class="navbar-brand" href="#">Mo-Djib Consulting</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#formations">Formations</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#audit">Audit</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#accompagnement">Accompagnement</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#pack-hygiene">Pack Hygiène</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#actualites">Actualités</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#contactez-nous">Contactez-nous</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<!-- Banner Section -->
<section class="banner">
    <div class="container">
        <div class="row">
            <div class="col-md-12">
                <h1>Bienvenue chez Mo-Djib Consulting</h1>
                <p>Votre partenaire mondial pour la qualité, l'hygiène et la sécurité alimentaire</p>
            </div>
        </div>
    </div>
</section>

<!-- Services Section -->
<section id="services" class="services">
    <div class="container">
        <div class="row">
            <div class="col-md-4">
                <div class="service-item">
                    <img src="https://via.placeholder.com/150" alt="Formations">
                    <h3>Formations</h3>
                    <p>Des formations de haute qualité adaptées à vos besoins.</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="service-item">
                    <img src="https://via.placeholder.com/150" alt="Audit">
                    <h3>Audit</h3>
                    <p>Des services d'audit sur mesure pour garantir la qualité.</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="service-item">
                    <img src="https://via.placeholder.com/150" alt="Accompagnement">
                    <h3>Accompagnement</h3>
                    <p>Nous vous accompagnons dans la mise en place de plans d'action.</p>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-4">
                <div class="service-item">
                    <img src="https://via.placeholder.com/150" alt="Pack Hygiène">
                    <h3>Pack Hygiène</h3>
                    <p>Optez pour notre pack hygiène complet pour l'excellence.</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="service-item">
                    <img src="https://via.placeholder.com/150" alt="Actualités">
                    <h3>Actualités</h3>
                    <p>Tenez-vous informé des dernières actualités dans notre domaine.</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="service-item">
                    <img src="https://via.placeholder.com/150" alt="Contactez-nous">
                    <h3>Contactez-nous</h3>
                    <p>Nous sommes là pour répondre à toutes vos questions.</p>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Contact Section -->
<section id="contactez-nous" class="contact">
    <div class="container">
        <div class="row">
            <div class="col-md-12">
                <h2>Contactez-nous</h2>
                <p>Vous souhaitez en savoir plus sur nos services ou discuter de vos besoins spécifiques en matière de qualité, d'hygiène et de sécurité alimentaire ? N'hésitez pas à nous contacter dès aujourd'hui. Notre équipe est là pour répondre à toutes vos questions et vous aider à atteindre vos objectifs. Chez Mo-Djib Consulting, votre succès est notre priorité.</p>
            </div>
        </div>
    </div>
</section>

<!-- Footer Section -->
<footer>
    <div class="container">
        <div class="row">
            <div class="col-md-12">
                <p>&copy; 2024 Mo-Djib Consulting. Tous droits réservés.</p>
            </div>
        </div>
    </div>
</footer>

<!-- Bootstrap Scripts -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>
</html>
