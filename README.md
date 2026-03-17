<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chat App - README</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.6;
            color: #24292e;
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            border-bottom: 1px solid #eaecef;
            padding-bottom: 0.3em;
        }
        h2 {
            border-bottom: 1px solid #eaecef;
            padding-bottom: 0.3em;
            margin-top: 24px;
        }
        code {
            background-color: #f6f8fa;
            border-radius: 3px;
            padding: 0.2em 0.4em;
            font-family: 'SF Mono', Monaco, Consolas, 'Liberation Mono', 'Courier New', monospace;
            font-size: 85%;
        }
        pre {
            background-color: #f6f8fa;
            border-radius: 3px;
            padding: 16px;
            overflow: auto;
        }
        pre code {
            background-color: transparent;
            padding: 0;
        }
        .container {
            background-color: #fff;
            border: 1px solid #e1e4e8;
            border-radius: 6px;
            padding: 20px;
        }
        .badge {
            display: inline-block;
            padding: 0.3em 0.6em;
            font-size: 0.85em;
            font-weight: 500;
            border-radius: 12px;
            background-color: #e7e7e7;
            color: #333;
            margin-right: 5px;
            text-decoration: none;
        }
        .tech-list {
            list-style: none;
            padding: 0;
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .tech-list li {
            background-color: #e7f3ff;
            color: #0366d6;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.9em;
        }
        .file-tree {
            background-color: #f8f9fa;
            border-left: 4px solid #0366d6;
            padding: 15px;
            border-radius: 4px;
            font-family: monospace;
        }
        .file-tree ul {
            list-style-type: none;
            padding-left: 20px;
        }
        .file-tree li {
            margin: 5px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>💬 Chat App</h1>
        <p>
            <span class="badge">Java</span>
            <span class="badge">Spring Boot</span>
            <span class="badge">Maven</span>
            <span class="badge">WebSocket</span>
            <span class="badge">Em desenvolvimento</span>
        </p>

        <p>
            Este repositório contém o código-fonte de uma aplicação de chat em tempo real, desenvolvida com Java e Spring Boot. 
            O projeto utiliza WebSockets para comunicação bidirecional entre cliente e servidor, permitindo troca de mensagens instantâneas.
        </p>

        <h2>📁 Estrutura do Projeto</h2>
        <p>A estrutura atual do repositório é a seguinte:</p>
        <div class="file-tree">
            📦 chat<br>
            ├── 📂 .mvn/wrapper          # Configurações do Maven Wrapper<br>
            ├── 📂 src                    # Código-fonte principal<br>
            │   ├── 📂 main<br>
            │   │   ├── 📂 java           # Classes Java da aplicação<br>
            │   │   └── 📂 resources      # Arquivos de configuração e estáticos<br>
            │   └── 📂 test                # Testes unitários<br>
            ├── 📄 .gitattributes         # Configurações de atributos Git<br>
            ├── 📄 .gitignore              # Arquivos ignorados pelo Git<br>
            ├── 📄 mvnw                     # Maven Wrapper (Unix)<br>
            ├── 📄 mvnw.cmd                 # Maven Wrapper (Windows)<br>
            ├── 📄 pom.xml                   # Configuração do Maven e dependências<br>
            └── 👤 MirellaArtischeff         # Primeiro commit (04/01/2026)<br>
        </div>

        <h2>✨ Funcionalidades (previstas)</h2>
        <ul>
            <li>Comunicação em tempo real via WebSocket</li>
            <li>Múltiplas salas de chat</li>
            <li>Notificações de entrada/saída de usuários</li>
            <li>Histórico de mensagens</li>
            <li>Interface web simples e responsiva</li>
        </ul>

        <h2>🛠️ Tecnologias Utilizadas</h2>
        <ul class="tech-list">
            <li>Java 21+</li>
            <li>Spring Boot</li>
            <li>Spring WebSocket</li>
            <li>Maven</li>
            <li>HTML/CSS/JavaScript (para o frontend básico)</li>
            <li>STOMP sobre WebSockets</li>
        </ul>

        <h2>🚀 Como Executar o Projeto</h2>
        <p>Para executar a aplicação localmente, siga os passos abaixo:</p>
        <ol>
            <li><strong>Clone o repositório:</strong>
                <pre><code>git clone https://github.com/Marcus-Austin/chat.git</code></pre>
            </li>
            <li><strong>Acesse a pasta do projeto:</strong>
                <pre><code>cd chat</code></pre>
            </li>
            <li><strong>Execute com Maven Wrapper:</strong>
                <pre><code>./mvnw spring-boot:run  # No Linux/macOS</code></pre>
                <pre><code>mvnw.cmd spring-boot:run  # No Windows</code></pre>
            </li>
            <li><strong>Acesse no navegador:</strong>
                <pre><code>http://localhost:8080</code></pre>
            </li>
        </ol>

        <h2>📌 Observações</h2>
        <ul>
           
            <li>As funcionalidades descritas acima são baseadas na estrutura esperada para uma aplicação de chat com Spring Boot e WebSocket; consulte o código-fonte para detalhes precisos.</li>
            <li>Este README será atualizado conforme o projeto evolui.</li>
        </ul>

        <h2>🤝 Contribuição</h2>
        <p>
            Contribuições são bem-vindas! Sinta-se à vontade para abrir <em>issues</em> ou enviar <em>pull requests</em> com melhorias, correções ou novas funcionalidades.
        </p>

      

        <hr>
        <p align="center">
            Desenvolvido com ❤️ por <a href="https://github.com/Marcus-Austin">Marcus-Austin</a> 
        </p>
    </div>
</body>
</html>
