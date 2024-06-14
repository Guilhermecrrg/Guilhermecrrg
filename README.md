<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nome do Projeto</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px;
            background: #fff;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            color: #333;
        }
        pre {
            background: #f4f4f4;
            padding: 10px;
            border: 1px solid #ddd;
            overflow-x: auto;
        }
        code {
            background: #f4f4f4;
            padding: 2px 4px;
            border-radius: 4px;
        }
        .badge {
            display: inline-block;
            padding: 5px;
            margin-right: 5px;
            border-radius: 4px;
            color: #fff;
        }
        .badge-success {
            background-color: #28a745;
        }
        .badge-info {
            background-color: #17a2b8;
        }
        .badge-warning {
            background-color: #ffc107;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Nome do Projeto</h1>

        <p>
            <span class="badge badge-success">Status: Active</span>
            <span class="badge badge-info">Versão: 1.0.0</span>
            <span class="badge badge-warning">Licença: MIT</span>
        </p>

        <p>Descrição curta do projeto, explicando de forma concisa o que ele faz e seu propósito.</p>

        <h2>Índice</h2>
        <ul>
            <li><a href="#instalacao">Instalação</a></li>
            <li><a href="#uso">Uso</a></li>
            <li><a href="#funcionalidades">Funcionalidades</a></li>
            <li><a href="#contribuicao">Contribuição</a></li>
            <li><a href="#licenca">Licença</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>

        <h2 id="instalacao">Instalação</h2>
        <ol>
            <li>Clone o repositório:
                <pre><code>git clone https://github.com/usuario/projeto.git</code></pre>
            </li>
            <li>Entre no diretório do projeto:
                <pre><code>cd projeto</code></pre>
            </li>
            <li>Instale as dependências:
                <pre><code>npm install</code></pre>
            </li>
        </ol>

        <h2 id="uso">Uso</h2>
        <p>Instruções de uso do projeto:</p>
        <pre><code>npm start</code></pre>
        <p>Para mais detalhes, consulte a <a href="docs/documentation.md">documentação</a>.</p>

        <h2 id="funcionalidades">Funcionalidades</h2>
        <ul>
            <li><strong>Funcionalidade 1:</strong> Descrição da funcionalidade 1.</li>
            <li><strong>Funcionalidade 2:</strong> Descrição da funcionalidade 2.</li>
            <li><strong>Funcionalidade 3:</strong> Descrição da funcionalidade 3.</li>
        </ul>

        <h2 id="contribuicao">Contribuição</h2>
        <p>Se você quiser contribuir com o projeto, siga os passos abaixo:</p>
        <ol>
            <li>Faça um fork do repositório.</li>
            <li>Crie uma branch para a sua feature (<code>git checkout -b feature/MinhaFeature</code>).</li>
            <li>Commit suas alterações (<code>git commit -m 'Adiciona MinhaFeature'</code>).</li>
            <li>Faça um push para a branch (<code>git push origin feature/MinhaFeature</code>).</li>
            <li>Abra um Pull Request.</li>
        </ol>
        <p>Leia o arquivo <a href="CONTRIBUTING.md">CONTRIBUTING</a> para mais detalhes sobre o nosso código de conduta e o processo de submissão de pull requests.</p>

        <h2 id="licenca">Licença</h2>
        <p>Distribuído sob a licença MIT. Veja <code>LICENSE</code> para mais informações.</p>

        <h2 id="contato">Contato</h2>
        <p>Seu Nome - <a href="https://twitter.com/seutwitter">@seutwitter</a> - seuemail@example.com</p>
        <p>Link do Projeto: <a href="https://github.com/usuario/projeto">https://github.com/usuario/projeto</a></p>
    </div>
</body>
</html>
