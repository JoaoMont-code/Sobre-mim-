<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio</title>
    <link rel="stylesheet" href="styles.css">
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
            width: 50px;
            height: 50px;
            margin: 10px;
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
    </style>
</head>
<body>

<header>
    <h1>Meu Portfólio</h1>
    <p>Desenvolvedor Python</p>
</header>

<div class="projects">
    <div class="project">
        <h2>Projeto 1</h2>
        <p>Descrição do Projeto 1.</p>
        <img src="https://www.python.org/community/logos/python-logo-master-v3-TM.png" alt="Ícone Python" class="icon">
    </div>
    <div class="project">
        <h2>Projeto 2</h2>
        <p>Descrição do Projeto 2.</p>
        <img src="https://www.python.org/community/logos/python-logo-master-v3-TM.png" alt="Ícone Python" class="icon">
    </div>
    <div class="project">
        <h2>Projeto 3</h2>
        <p>Descrição do Projeto 3.</p>
        <img src="https://www.python.org/community/logos/python-logo-master-v3-TM.png" alt="Ícone Python" class="icon">
    </div>
</div>

<a href="https://github.com/seu-usuario" class="github-link">Veja meu GitHub</a>

</body>
</html>
