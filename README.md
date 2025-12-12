<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kaio Manfro - Desenvolvimento de Software e IoT</title>
    <style>
        /* Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }

        /* Container */
        .container {
            width: 80%;
            margin: auto;
        }

        /* Header */
        header {
            background-color: #0078d4;
            color: white;
            text-align: center;
            padding: 50px 0;
            opacity: 0;
            animation: fadeIn 1s forwards;
        }

        header h1 {
            font-size: 3em;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2em;
        }

        /* Animations */
        @keyframes fadeIn {
            0% {
                opacity: 0;
            }

            100% {
                opacity: 1;
            }
        }

        @keyframes slideIn {
            0% {
                transform: translateX(-100%);
                opacity: 0;
            }

            100% {
                transform: translateX(0);
                opacity: 1;
            }
        }

        @keyframes scaleUp {
            0% {
                transform: scale(0.9);
                opacity: 0;
            }

            100% {
                transform: scale(1);
                opacity: 1;
            }
        }

        /* Main content */
        .content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            margin-top: 20px;
            animation: fadeIn 1.5s forwards;
        }

        .section {
            width: 48%;
            margin-bottom: 30px;
            opacity: 0;
            animation: slideIn 1s ease-out forwards;
        }

        .section:nth-child(1) {
            animation-delay: 0.5s;
        }

        .section:nth-child(2) {
            animation-delay: 1s;
        }

        .section h2 {
            font-size: 2em;
            margin-bottom: 10px;
        }

        .section p {
            font-size: 1.1em;
            margin-bottom: 15px;
        }

        .section ul {
            list-style: none;
            padding-left: 0;
        }

        .section ul li {
            font-size: 1.1em;
            margin-bottom: 5px;
        }

        .section a {
            color: #0078d4;
            text-decoration: none;
        }

        .section a:hover {
            text-decoration: underline;
        }

        /* Project cards */
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            animation: fadeIn 2s forwards;
        }

        .project-card {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
            opacity: 0;
            animation: scaleUp 1s ease-out forwards;
        }

        .project-card:nth-child(1) {
            animation-delay: 1.5s;
        }

        .project-card:nth-child(2) {
            animation-delay: 2s;
        }

        .project-card h3 {
            font-size: 1.5em;
            margin-bottom: 10px;
        }

        .project-card p {
            font-size: 1.1em;
            margin-bottom: 10px;
        }

        .project-card a {
            color: #0078d4;
            text-decoration: none;
            font-weight: bold;
        }

        .project-card a:hover {
            text-decoration: underline;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 30px 0;
            margin-top: 40px;
            opacity: 0;
            animation: fadeIn 2s forwards;
        }

        footer a {
            color: #fff;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* Responsive design */
        @media (max-width: 768px) {
            .content {
                flex-direction: column;
            }

            .section {
                width: 100%;
            }

            .projects {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>

<body>
    <header>
        <div class="container">
            <h1>Olá, sou Kaio Manfro! 🚀</h1>
            <p>Estudante de Técnico em Informática no **IFRS** | Apaixonado por Desenvolvimento de Software, Web e IoT</p>
        </div>
    </header>

    <div class="container content">
        <!-- Sobre mim -->
        <div class="section">
            <h2>🎯 Sobre Mim</h2>
            <p>Estou focado em aprimorar minhas habilidades e construir projetos que façam a diferença. Com uma base sólida em diversas linguagens e frameworks, busco sempre aprender mais e aplicar meus conhecimentos em soluções práticas.</p>
            <p>Sou entusiasta de **Internet das Coisas (IoT)**, explorando o mundo dos dispositivos conectados com **ESP32** e **Arduino** para criar sistemas inteligentes e inovadores.</p>
        </div>

        <!-- Tecnologias & Ferramentas -->
        <div class="section">
            <h2>💻 Tecnologias & Ferramentas</h2>
            <ul>
                <li>🟨 JavaScript</li>
                <li>🟦 C#</li>
                <li>🟢 Node.js</li>
                <li>☕ Java</li>
                <li>🐍 Python</li>
                <li>🔥 Firebase</li>
                <li>🗄️ MySQL</li>
                <li>🐘 PHP</li>
                <li>🌐 HTML</li>
                <li>🎨 CSS</li>
            </ul>
        </div>
    </div>

    <div class="container content">
        <!-- Desenvolvimento de Software & Web -->
        <div class="section">
            <h2>🚀 Desenvolvimento de Software & Web</h2>
            <p>Minha paixão é desenvolver aplicações robustas, escaláveis e eficientes. Tenho experiência em:</p>
            <ul>
                <li><strong>Front-end:</strong> JavaScript moderno, integração com APIs e frameworks.</li>
                <li><strong>Back-end:</strong> Node.js, C# (com .NET), Java, criação e manutenção de APIs RESTful.</li>
                <li><strong>Banco de Dados:</strong> Modelagem e consultas em MySQL, integração com Firebase para backend em nuvem.</li>
                <li><strong>Projetos Web:</strong> Criação de sites responsivos, acessíveis e otimizados.</li>
            </ul>
        </div>

        <!-- Projetos em destaque -->
        <div class="section">
            <h2>🔗 Projetos em Destaque</h2>
            <div class="projects">
                <div class="project-card">
                    <h3>ESP32 - Interpretação de Morse</h3>
                    <p>Projeto simples e educativo utilizando o ESP32 para transmitir mensagens em código Morse através de um LED.</p>
                    <a href="https://github.com/dev-kaio/ESP32-LedMorse.git" target="_blank">Ver no GitHub</a>
                </div>

                <div class="project-card">
                    <h3>Calendário de Cursos</h3>
                    <p>Aplicação web para facilitar o acesso a informações de cursos em andamento e que estão para começar.</p>
                    <a href="https://github.com/dev-kaio/CalendarioSENAI.git" target="_blank">Ver no GitHub</a>
                </div>

                <div class="project-card">
                    <h3>Controle de Ferramentaria</h3>
                    <p>Sistema PWA para gerenciar a retirada e devolução de ferramentas por alunos em oficinas ou laboratórios escolares.</p>
                    <a href="https://dev-kaio.github.io/Controle-de-Ferramentas/" target="_blank">Ver projeto online</a>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <p>Vamos conversar? 🚀</p>
        <p><a href="https://www.linkedin.com/in/dev-kaio" target="_blank">LinkedIn</a></p>
        <p>&copy; 2025 Kaio Manfro. Todos
