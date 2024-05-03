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
            background-color: #333;
            border-radius: 0; /* Rounded rectangle */
        }
        .navbar-nav .nav-link {
            color: white;
            transition: color 0.3s, background-color 0.3s; /* Transition for glowing effect */
        }
        .navbar-nav .nav-link:hover {
            color: #FFA500; /* Modern orangish color */
            background-color: rgba(255, 165, 0, 0.1); /* Orange background */
        }
        .navbar-brand {
            color: white;
            font-size: 24px;
        }
        /* Body padding to compensate for fixed navbar */
        body {
            padding-top: 56px; /* Height of the navbar */
            margin-left: 200px; /* Adjusted to accommodate the sidebar */
        }
        /* Sidebar Styles */
        #sidebar {
            position: fixed;
            top: 0;
            left: 0;
            bottom: 0;
            z-index: 1000;
            background-color: #333;
            width: 200px;
            padding-top: 56px; /* Height of the navbar */
            overflow-y: auto;
            transition: all 0.3s;
        }
        #sidebar ul {
            list-style-type: none;
            padding: 0;
        }
        #sidebar ul li {
            padding: 10px;
            color: white;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        #sidebar ul li:hover {
            background-color: rgba(255, 255, 255, 0.1);
        }
        #content {
            margin-left: 200px; /* Adjusted to accommodate the sidebar */
            padding: 20px;
        }
        /* Section Styles */
        section {
            margin-top: 20px;
            padding: 20px;
            border-radius: 10px;
            background-color: #f9f9f9;
            box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.1);
        }
        section h1 {
            color: #007bff;
            margin-bottom: 20px;
        }
        /* Card Styles */
        .card {
            border: none;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s;
            cursor: pointer;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .card-body {
            text-align: center;
        }
        /* Code Styles */
        pre {
            background-color: #f8f9fa;
            border: 1px solid #dee2e6;
            border-radius: 5px;
            padding: 10px;
            overflow-x: auto;
            position: relative;
            cursor: pointer;
        }
        pre:hover::after {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 255, 0.1); /* Blue color when hovered */
            border-radius: 5px;
            z-index: 1;
        }
        pre:hover::before {
            content: "\f0ea"; /* FontAwesome copy icon */
            font-family: "Font Awesome 5 Free";
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 20px;
            color: #007bff;
            z-index: 2;
        }
        .copy-box {
            border: 1px solid #dee2e6;
            border-radius: 5px;
            padding: 10px;
            background-color: #f8f9fa;
            margin-top: 20px;
            cursor: pointer;
            display: inline-block;
            position: relative;
        }
        .copy-box:hover {
            background-color: #e9ecef;
        }
        .copy-box::before {
            content: "\f0c5"; /* FontAwesome copy icon */
            font-family: "Font Awesome 5 Free";
            position: absolute;
            top: 50%;
            left: 5px;
            transform: translateY(-50%);
            font-size: 18px;
            color: #007bff;
        }
    </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
        <a class="navbar-brand" href="#">Mo-Djib Consulting</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#about">À propos</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#services">Nos Services</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#approach">Notre Approche</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#team">Notre Équipe</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#contact">Contactez-nous</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<!-- Sidebar -->
<div id="sidebar">
    <ul>
        <li><a href="#about">À propos</a></li>
        <li><a href="#services">Nos Services</a></li>
        <li><a href="#approach">Notre Approche</a></li>
        <li><a href="#team">Notre Équipe</a></li>
        <li><a href="#contact">Contactez-nous</a></li>
    </ul>
</div>

<!-- About Section -->
<section id="about">
    <div class="container">
        <h1>À propos de Mo-Djib Consulting</h1>
        <p>Chez Mo-Djib Consulting, nous sommes bien plus qu'un simple cabinet de conseil, d’audit et de formation. Nous sommes une équipe passionnée et dévouée, prête à accompagner les porteurs de projets et les chefs d'entreprise, quel que soit leur domaine d'activité.</p>
    </div>
</section>

<!-- Services Section -->
<section id="services">
    <div class="container">
        <h1>Nos Services</h1>
        <h2>Formations</h2>
        <ul>
            <li>Formations HACCP</li>
            <li>Formation aux bonnes pratiques d'hygiène alimentaire en restauration collective</li>
            <li>Formation aux bonnes pratiques d'hygiène alimentaire pour les boucheries-charcuteries</li>
            <li>Hygiène alimentaire en restauration commerciale</li>
        </ul>
        <h2>Services Complémentaires</h2>
        <ul>
            <li>Audit</li>
            <li>Accompagnement</li>
            <li>Pack Hygiène</li>
        </ul>
    </div>
</section>

<!-- Approach Section -->
<section id="approach">
    <div class="container">
        <h1>Notre Approche</h1>
        <p>Chez Mo-Djib Consulting, nous croyons en une approche holistique de la qualité, de l'hygiène et de la sécurité alimentaire. Nous ne nous contentons pas de fournir des formations standard, mais nous nous engageons à comprendre les spécificités de votre entreprise et à concevoir des solutions sur mesure pour répondre à vos besoins uniques.</p>
    </div>
</section>

<!-- Team Section -->
<section id="team">
    <div class="container">
        <h1>Notre Équipe</h1>
        <p>Notre équipe est composée d'experts chevronnés dans le domaine de la qualité, de l'hygiène et de la sécurité alimentaire. Leur expérience et leur expertise nous permettent d'offrir des services de haute qualité et des conseils avisés à nos clients.</p>
    </div>
</section>

<!-- Contact Section -->
<section id="contact">
    <div class="container">
        <h1>Contactez-nous</h1>
        <p>Vous souhaitez en savoir plus sur nos services ou discuter de vos besoins spécifiques en matière de qualité, d'hygiène et de sécurité alimentaire ? N'hésitez pas à nous contacter dès aujourd'hui. Notre équipe est là pour répondre à toutes vos questions et vous aider à atteindre vos objectifs. Chez Mo-Djib Consulting, votre succès est notre priorité.</p>
    </div>
</section>

<!-- Bootstrap Scripts -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

<!-- JavaScript for Smooth Scrolling and Active Navigation -->
<script>
    // Smooth scrolling for sidebar links
    document.querySelectorAll('#sidebar a').forEach(anchor => {
        anchor.addEventListener('click', function (e) {
            e.preventDefault();

            document.querySelector(this.getAttribute('href')).scrollIntoView({
                behavior: 'smooth'
            });
        });
    });
</script>

</body>
</html>
