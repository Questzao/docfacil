# Site de Download de Arquivos

Este projeto é um site simples que permite aos usuários fazer download de arquivos.

 Estrutura do Projeto

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Downloads de Documentos</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }

        header {
            background: #007BFF;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        main {
            padding: 20px;
            max-width: 800px;
            margin: auto;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #007BFF;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            margin: 15px 0;
            border-bottom: 1px solid #ddd;
            padding-bottom: 10px;
        }

        a {
            text-decoration: none;
            color: #007BFF;
            font-weight: bold;
            transition: color 0.3s;
        }

        a:hover {
            color: #0056b3;
        }

        footer {
            text-align: center;
            padding: 15px 0;
            background: #007BFF;
            color: #fff;
            position: relative;
            bottom: 0;
            width: 100%;
            margin-top: 20px;
            border-radius: 0 0 8px 8px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Documentos para Download</h1>
    </header>
    <main>
        <h2>Documentos Disponíveis</h2>
        <ul>
            <li><a href="Nova pasta.zip" download>Documento 1</a></li>
            <li><a href="Nova pasta.zip" download>Documento 2</a></li>
            <li><a href="Nova pasta.zip" download>Documento 3</a></li>
        </ul>
    </main>
    <footer>
        <p>&copy; 2024 Seu Nome</p>
    </footer>
</body>
</html>


### Instruções

1. **Salve o conteúdo acima em um arquivo chamado `README.md`.**
2. **Crie a estrutura de pastas conforme indicado.**
3. **Adicione os arquivos que deseja disponibilizar na pasta `files`.**
4. **Abra o `index.html` em um navegador para testar.**

Se precisar de mais alguma coisa ou de ajustes, é só avisar!
