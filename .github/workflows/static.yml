<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Nathan LEGUILLON</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            background-color: #0d1117;
            color: #c9d1d9;
            overflow: hidden;
        }

        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(13, 17, 23, 0.9);
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
            display: flex;
            justify-content: center;
            padding: 10px 0;
            z-index: 1000;
        }

        nav a {
            color: #58a6ff;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1rem;
            font-weight: bold;
            text-transform: uppercase;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #1f6feb;
        }

        section {
            height: 100vh;
            display: none;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
        }

        section.active {
            display: flex;
            animation: fadeIn 1s ease-in-out;
        }

        h1, h2 {
            color: #58a6ff;
            margin: 0;
            font-weight: 700;
        }

        p {
            font-size: 1.2rem;
            line-height: 1.6;
            max-width: 600px;
            color: #8b949e;
        }

        .brand {
            position: fixed;
            top: 10px;
            left: 10px;
            font-size: 1.5rem;
            font-weight: bold;
            color: #58a6ff;
            background: rgba(13, 17, 23, 0.8);
            padding: 5px 10px;
            border-radius: 5px;
            z-index: 1001;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
        }

        footer {
            position: fixed;
            bottom: 10px;
            width: 100%;
            text-align: center;
            font-size: 0.9rem;
            color: #8b949e;
        }

        .competence-cards, .presentation-cards, .formation-cards {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 30px;
        }

        .card {
            background: #161b22;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
            width: 300px;
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 12px rgba(0, 0, 0, 0.5);
        }

        .card h2 {
            color: #58a6ff;
            margin-bottom: 10px;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <div class="brand">Nathan LEGUILLON</div>
    <nav>
        <a href="#presentation" class="nav-link">Présentation</a>
        <a href="#competence" class="nav-link">Compétence</a>
        <a href="#formation" class="nav-link">Formation</a>
        <a href="#experience" class="nav-link">Expérience</a>
        <a href="#cv" class="nav-link">CV</a>
        <a href="#veille" class="nav-link">Veille Technologique</a>
        <a href="#contact" class="nav-link">Contact</a>
    </nav>

    <section id="presentation" class="active">
        <h1>Bienvenue</h1>
        <p>Découvrez mon portfolio et apprenez-en plus sur moi. Naviguez à travers les catégories pour explorer mes compétences, mon expérience et bien plus encore.</p>
        <div class="presentation-cards">
            <div class="card">
                <h2>Présentation rapide 1</h2>
                <p>Jeune et futur ingénieur IA, actuellement en BTS SIO 1ère année, ambitieux, débrouillard et convainquant.</p>
            </div>
            <div class="card">
                <h2>Présentation rapide 2</h2>
                <p>Je suis passionné par la technologie et la création de solutions innovantes.</p>
            </div>
        </div>
    </section>

    <section id="competence">
        <h1>Compétences</h1>
        <p>Voici un aperçu de mes compétences techniques et personnelles qui me permettent de réaliser des projets variés avec succès.</p>
        <div class="competence-cards">
            <div class="card">
                <h2>Développement Web</h2>
                <p>Création de sites modernes et performants en utilisant HTML, CSS, JavaScript, et des frameworks comme React et Vue.js.</p>
            </div>
            <div class="card">
                <h2>Réseau & Système</h2>
                <p>Expérience en Système Informatique et Réseau.Notion acquises de Python et SQL</p>
            </div>
            <div class="card">
                <h2>Soft Skills</h2>
                <p>Capacités de communication, résolution de problèmes et gestion de projets en équipe agile.</p>
            </div>
        </div>
    </section>

    <section id="formation">
        <h1>Formation</h1>
        <p>Voici un aperçu de mon parcours éducatif et des certifications que j'ai obtenues pour développer mes compétences.</p>
        <div class="formation-cards">
            <div class="card">
                <h2>Formation 1</h2>
                <p>J'ai obtenu un baccalauréat en informatique en SN (Systèmes Numériques), où j'ai appris les bases du développement logiciel.</p>
            </div>
            <div class="card">
                <h2>Formation 2</h2>
                <p>Formation en développement web avec des technologies modernes comme React et Node.js.</p>
            </div>
            <div class="card">
                <h2>Formation 3</h2>
                <p>Certification en cours avec RootMe, spécialisée dans la cybersécurité et le hacking éthique.</p>
            </div>
        </div>
    </section>

    <section id="experience">
        <h1>Expérience</h1>
        <p>Mon expérience professionnelle reflète ma capacité à résoudre des problèmes et à apporter de la valeur à chaque projet.</p>
    </section>

    <section id="cv">
        <h1>Mon CV</h1>
        <p>Téléchargez mon CV pour en savoir plus sur mes qualifications et mon parcours.</p>

        <a href="cv-nathan.pdf" download>
            <button style="background-color: #58a6ff; color: white; padding: 10px 20px; border: none; border-radius: 5px; font-size: 1rem; cursor: pointer;">
                Télécharger mon CV ! 
            </button>
        </a>
        
    </section>

    <section id="veille">
        <h1>Veille Technologique</h1>
        <p>Restez à jour avec mes recherches sur les dernières tendances et innovations technologiques.</p>
        
        <div class="card">
            <h2>Rien à voir ici !</h2>
            <p>En attente de nouveauté ! </p>
        </div>
    </section>

    <section id="contact">
        <h1>Contact</h1>
        <p>Envoyez-moi un message ou connectez-vous avec moi sur les réseaux sociaux. Je suis toujours ouvert à de nouvelles opportunités.</p>
        <div>
            <h2>Envoyer un Email</h2>
            <form action="mailto:votre.email@example.com" method="post" enctype="text/plain">
                <label for="name">Nom :</label><br>
                <input type="text" id="name" name="name" required><br><br>

                <label for="email">Email :</label><br>
                <input type="email" id="email" name="email" required><br><br>

                <label for="message">Message :</label><br>
                <textarea id="message" name="message" rows="4" required></textarea><br><br>

                <button type="submit">Envoyer</button>
            </form>
        </div>
        <div>
            <h2>Connectez-vous avec moi :</h2>
            <a href="https://github.com/Natemps05"_blank">GitHub</a> | 
            <a href="https://www.linkedin.com/in/nathan-leguillon-2ba896342/" target="_blank">LinkedIn</a>
        </div>
    </section>

    <footer>
        © 2025 Nathan LEGUILLON - Tous droits réservés
    </footer>

    <script>
        const sections = document.querySelectorAll('section');
        const navLinks = document.querySelectorAll('.nav-link');

        function activateSection(id) {
            sections.forEach(section => {
                section.classList.remove('active');
                if (section.id === id) {
                    section.classList.add('active');
                }
            });
        }

        navLinks.forEach(link => {
            link.addEventListener('click', (e) => {
                e.preventDefault();
                const targetId = link.getAttribute('href').substring(1);
                activateSection(targetId);
            });
        });
    </script>
</body>
</html>
