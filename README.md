<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estudos Interativos</title>
    <style>
        body {
            background-color: #f0f0f0;
            color: #333;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #4CAF50;
            color: #fff;
            padding: 15px 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav {
            background-color: #333;
            color: #fff;
            display: flex;
            justify-content: space-around;
            padding: 10px 0;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 15px;
        }

        nav a:hover {
            background-color: #575757;
            border-radius: 5px;
        }

        .container {
            padding: 20px;
        }

        .section {
            margin-bottom: 30px;
        }

        .section h2 {
            margin-bottom: 10px;
        }

        .forums, .resources, .schedule, .faq {
            background-color: #fff;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .forum-post, .resource-item, .schedule-item, .faq-item {
            padding: 10px 0;
            border-bottom: 1px solid #eee;
        }

        .forum-post:last-child, .resource-item:last-child, .schedule-item:last-child, .faq-item:last-child {
            border-bottom: none;
        }

        footer {
            background-color: #4CAF50;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        /* Estilos responsivos */
        @media (min-width: 600px) {
            .container {
                display: flex;
                flex-wrap: wrap;
                gap: 20px;
            }

            .section {
                flex: 1 1 calc(50% - 20px);
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Estudos Interativos</h1>
    </header>
    <nav>
        <a href="#forums">Fóruns</a>
        <a href="#resources">Recursos</a>
        <a href="#schedule">Agenda</a>
        <a href="#faq">FAQ</a>
    </nav>
    <div class="container">
        <div id="forums" class="section forums">
            <h2>Fóruns de Discussão</h2>
            <div class="forum-post">Post de fórum 1</div>
            <div class="forum-post">Post de fórum 2</div>
            <div class="forum-post">Post de fórum 3</div>
            <!-- Adicione mais posts conforme necessário -->
        </div>
        <div id="resources" class="section resources">
            <h2>Recursos de Estudo</h2>
            <div class="resource-item">Recurso 1</div>
            <div class="resource-item">Recurso 2</div>
            <div class="resource-item">Recurso 3</div>
            <!-- Adicione mais recursos conforme necessário -->
        </div>
        <div id="schedule" class="section schedule">
            <h2>Agenda de Aulas</h2>
            <div class="schedule-item">Aula 1</div>
            <div class="schedule-item">Aula 2</div>
            <div class="schedule-item">Aula 3</div>
            <!-- Adicione mais aulas conforme necessário -->
        </div>
        <div id="faq" class="section faq">
            <h2>Perguntas Frequentes</h2>
            <div class="faq-item">Pergunta 1</div>
            <div class="faq-item">Pergunta 2</div>
            <div class="faq-item">Pergunta 3</div>
            <!-- Adicione mais perguntas conforme necessário -->
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Estudos Interativos. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
