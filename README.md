<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        header {
            text-align: center;
            margin-bottom: 20px;
        }
        h1 {
            color: #333;
        }
        .icon {
            font-size: 50px;
            margin: 10px;
            color: #4B8BBE; /* Cor do Python */
        }
        .projects {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .project {
            background: white;
            padding: 15px;
            margin: 10px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 80%;
            text-align: center;
        }
        .github-link {
            display: block;
            margin-top: 20px;
            color: #0366d6;
            text-decoration: none;
        }
        .social-icons {
            margin-top: 20px;
        }
        .social-icons a {
            margin: 0 10px;
            color: #333;
            text-decoration: none;
        }
    </style>
</head>
<body>

<header>
    <h1>Meu Portfólio</h1>
    <p>Desenvolvedor Python</p>
    <div class="icon">
        <i class="fab fa-python"></i>
    </div>
</header>

<div class="projects">
    <div class="project">
        <h2>Projeto 1</h2>
        <p>Descrição do Projeto 1: Um aplicativo em Python para gerenciar tarefas.</p>
        <i class="fab fa-python icon"></i>
    </div>
    <div class="project">
        <h2>Projeto 2</h2>
        <p>Descrição do Projeto 2: Um site desenvolvido com Flask.</p>
        <i class="fab fa-python icon"></i>
    </div>
    <div class="project">
        <h2>Projeto 3</h2>
        <p>Descrição do Projeto 3: Um script de automação usando Python.</p>
        <i class="fab fa-python icon"></i>
    </div>
</div>

<a href="https://github.com/seu-usuario" class="github-link">Veja meu GitHub</a>

<div class="social-icons">
    <a href="https://linkedin.com/in/seu-usuario" target="_blank">
        <i class="fab fa-linkedin"></i>
    </a>
    <a href="https://twitter.com/seu-usuario" target="_blank">
        <i class="fab fa-twitter"></i>
    </a>
    <a href="https://github.com/seu-usuario" target="_blank">
        <i class="fab fa-github"></i>
    </a>
</div>

</body>
</html>
