<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bryan - Desarrollador Frontend</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --dark-bg: #0d1117;
            --card-bg: #161b22;
            --accent-color: #58a6ff;
            --text-color: #c9d1d9;
            --secondary-text: #8b949e;
            --border-color: #30363d;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: var(--dark-bg);
            color: var(--text-color);
            line-height: 1.6;
            padding: 20px;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
        }
        
        header {
            text-align: center;
            padding: 40px 20px;
            background-color: var(--card-bg);
            border-radius: 10px;
            margin-bottom: 30px;
            border: 1px solid var(--border-color);
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            color: var(--accent-color);
        }
        
        .tagline {
            font-size: 1.2rem;
            color: var(--secondary-text);
            margin-bottom: 15px;
        }
        
        .divider {
            height: 1px;
            background: var(--border-color);
            margin: 20px 0;
        }
        
        .section {
            background-color: var(--card-bg);
            border-radius: 10px;
            padding: 25px;
            margin-bottom: 25px;
            border: 1px solid var(--border-color);
        }
        
        h2 {
            color: var(--accent-color);
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        h2 i {
            font-size: 1.3rem;
        }
        
        .about-content p {
            margin-bottom: 15px;
            color: var(--text-color);
        }
        
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 15px;
        }
        
        .skill-category {
            margin-bottom: 25px;
        }
        
        .skill-category h3 {
            color: var(--accent-color);
            margin-bottom: 15px;
            padding-left: 10px;
            border-left: 3px solid var(--accent-color);
        }
        
        .skill-item {
            background-color: rgba(88, 166, 255, 0.1);
            padding: 12px 15px;
            border-radius: 6px;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 10px;
            transition: transform 0.3s ease, background-color 0.3s ease;
            border: 1px solid var(--border-color);
        }
        
        .skill-item:hover {
            transform: translateX(5px);
            background-color: rgba(88, 166, 255, 0.2);
        }
        
        .skill-item i {
            color: var(--accent-color);
            width: 20px;
        }
        
        .experience-item {
            margin-bottom: 25px;
        }
        
        .experience-item h3 {
            color: var(--accent-color);
            margin-bottom: 8px;
        }
        
        .date {
            color: var(--secondary-text);
            font-size: 0.9rem;
            margin-bottom: 10px;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        
        .social-link {
            color: var(--text-color);
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 8px;
            transition: color 0.3s ease;
            padding: 10px 15px;
            border-radius: 6px;
            background-color: rgba(88, 166, 255, 0.1);
            border: 1px solid var(--border-color);
        }
        
        .social-link:hover {
            color: var(--accent-color);
            background-color: rgba(88, 166, 255, 0.2);
        }
        
        .badge {
            display: inline-block;
            padding: 3px 8px;
            border-radius: 15px;
            font-size: 0.7rem;
            background-color: var(--accent-color);
            color: var(--dark-bg);
            margin-left: 8px;
            font-weight: bold;
        }
        
        @media (max-width: 768px) {
            .skills-container {
                grid-template-columns: 1fr;
            }
            
            .social-links {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Hola, soy Bryan 👋</h1>
            <p class="tagline">Desarrollador Frontend apasionado | Estudiante de Tecnología en ADS</p>
            <div class="divider"></div>
            <p>Innovador y siempre aprendiendo</p>
        </header>
        
        <section class="section">
            <h2><i class="fas fa-user"></i> Sobre mí</h2>
            <div class="about-content">
                <p>Soy un desarrollador junior apasionado por la programación, actualmente estudiando un tecnólogo en Análisis y Desarrollo de Software. Cuento con experiencia en diversas tecnologías y mi punto fuerte es el desarrollo web, especialmente el frontend.</p>
                <p>Me encanta innovar, aprender constantemente y enfrentar nuevos desafíos que me permitan crecer profesionalmente. Siempre estoy buscando oportunidades para aplicar mis conocimientos y adquirir nuevas habilidades.</p>
                <p>Me inclino especialmente por el desarrollo frontend, donde puedo combinar mi creatividad con habilidades técnicas para crear experiencias de usuario excepcionales.</p>
            </div>
        </section>
        
        <section class="section">
            <h2><i class="fas fa-laptop-code"></i> Habilidades Técnicas</h2>
            <div class="skills-container">
                <div class="skill-category">
                    <h3>Lenguajes de Programación</h3>
                    <div class="skill-item">
                        <i class="fab fa-js"></i>
                        <span>JavaScript</span>
                    </div>
                    <div class="skill-item">
                        <i class="fab fa-react"></i>
                        <span>React</span>
                    </div>
                    <div class="skill-item">
                        <i class="fab fa-node-js"></i>
                        <span>Node.js</span>
                    </div>
                    <div class="skill-item">
                        <i class="fas fa-code"></i>
                        <span>C</span>
                    </div>
                    <div class="skill-item">
                        <i class="fab fa-microsoft"></i>
                        <span>.NET</span>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h3>Desarrollo Web</h3>
                    <div class="skill-item">
                        <i class="fab fa-html5"></i>
                        <span>HTML5</span>
                    </div>
                    <div class="skill-item">
                        <i class="fab fa-css3-alt"></i>
                        <span>CSS3</span>
                    </div>
                    <div class="skill-item">
                        <i class="fab fa-css3"></i>
                        <span>Tailwind CSS</span>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h3>Bases de Datos</h3>
                    <div class="skill-item">
                        <i class="fas fa-database"></i>
                        <span>MySQL</span>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h3>Herramientas & DevOps</h3>
                    <div class="skill-item">
                        <i class="fab fa-docker"></i>
                        <span>Docker</span>
                    </div>
                    <div class="skill-item">
                        <i class="fas fa-terminal"></i>
                        <span>Nodemon</span>
                    </div>
                    <div class="skill-item">
                        <i class="fab fa-git-alt"></i>
                        <span>Git</span>
                    </div>
                    <div class="skill-item">
                        <i class="fab fa-github"></i>
                        <span>GitHub</span>
                    </div>
                </div>
                
                <div class="skill-category">
                    <h3>En Aprendizaje</h3>
                    <div class="skill-item">
                        <i class="fab fa-vuejs"></i>
                        <span>Vue.js</span>
                        <span class="badge">Nuevo</span>
                    </div>
                    <div class="skill-item">
                        <i class="fab fa-python"></i>
                        <span>Python</span>
                        <span class="badge">Nuevo</span>
                    </div>
                </div>
            </div>
        </section>
        
        <section class="section">
            <h2><i class="fas fa-graduation-cap"></i> Formación</h2>
            <div class="experience-item">
                <h3>Tecnólogo en Análisis y Desarrollo de Software</h3>
                <p class="date">En curso</p>
                <p>Formación en desarrollo de software, bases de datos, metodologías ágiles y gestión de proyectos.</p>
            </div>
            <div class="experience-item">
                <h3>Técnico en Sistemas</h3>
                <p>Conocimientos en mantenimiento de hardware, redes, soporte técnico y fundamentos de programación.</p>
            </div>
        </section>
        
        <section class="section">
            <h2><i class="fas fa-envelope"></i> Contáctame</h2>
            <p>¡Siéntete libre de contactarme para colaborar en proyectos o para cualquier oportunidad de desarrollo!</p>
            <div class="social-links">
                <a href="#" class="social-link">
                    <i class="fab fa-github"></i>
                    <span>GitHub</span>
                </a>
                <a href="#" class="social-link">
                    <i class="fab fa-linkedin"></i>
                    <span>LinkedIn</span>
                </a>
                <a href="#" class="social-link">
                    <i class="fas fa-envelope"></i>
                    <span>Email</span>
                </a>
            </div>
        </section>
    </div>
</body>
</html>
