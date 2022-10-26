# HTML
Minhas anotações de aprendizados HTML

- **O que é HTML?**
    
    HTML é a linguagem de marcação padrão para páginas da Web.
    
    Com HTML você pode criar seu próprio site. Uaauuu
    
---
Sugiro que façam vcs mesmos para ver o que vai mostrar na tela e também para fixar nesse seu cerebro :P
- h1-h6 - **título**
    
   
    ```html
    <div>
            <h1>Título do texto 1</h1>
            <h2>Título do texto 2</h2>
            <h3>Título do texto 3</h3>
            <h4>Título do texto 4</h4>
            <h5>Título do texto 5</h5>
            <h6>Título do texto 6</h6>
    </div>
    ```
    
- p - **paragrafo**
    
    ```html
    <p>
    		paragrafo
    </p>
    ```
    
- ul - **lista desordenada**
    
    ```html
    <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ul>
    ```
    
- ol - **lista ordenada**
    
    ```html
    <ol>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ol>
    ```
    
- dl dt dd - l****istas de Descrição****
    
    ```html
    <dl>
        <dt>Html</dt>
        <dd>- Hyper Text Markup Language</dd>
        <dt>CSS</dt>
        <dd>- Cascading Style Sheets</dd>
    </dl>
    ```
    
- button - **botão**
    
    ```html
    <button type="button">Click</button>
    ```
    
- img - **imagem**
    
    ```html
    <img src="https://picsum.photos/200/300" alt="Imagem carregada pela api" width="100px" height="100px">
    ```
    
- a href - **links**
    
    ```html
    <a href="http://example.com">
        Link!
    </a>
    ```
    
- **Tabelas**
    - `table>` define uma tabela HTML
    - `<tr>` define uma linha na tabela
    - `<th>` define um cabeçalho na tabela
    - `<td>` define uma célula da tabela
    
    ```html

    <table>
        <tr>
            <th>Id</th>
            <th>User</th>
        </tr>
        <tr>
            <td>12</td>
            <td>Jonh_doe</td>
        </tr>
        <tr>
            <td>14</td>
            <td>Janice_doe</td>
        </tr>
    </table>
    ```
    
- form - **formulario**
    
    ```html
    <form>
        <label for="nome">Nome:</label><br>
        <input type="text" id="nome" name="nome"><br>
        <label for="senha">Senha:</label><br>
        <input type="password" id="senha" name="senha">
    </form>
    ```
    
- **Titulo da pag**
    
    ```html
    <head>
        <link rel="stylesheet" href="style.css">
        <title>Titulo da pagina</title>
    </head>
    ```
    
- **Style dentro da head**
    
    ```html
    <head>
        <title>Titulo da pagina</title>
        <style>
            body{
                background-color: #e2e2e2;
            }
        </style>
    </head>
    ```
    
- **Script dentro do head**
    
    ```html
    <body>
        <div>
            <form>
                <label for="fname">Nome:</label><br>
                <input type="text" id="nome" name="nome"><br>
                <label for="lname">Senha:</label><br>
                <input type="password" id="senha" name="senha">
            </form>
        </div>
        <script src="script.js"></script>
        <script>
            const alerta = () => {
                alert("Script Javascript");
            }
            alerta();
        </script>
    </body>
    ```
    
- **Mudar elementos texto**
    
    ```html
    <b> - Texto negrito
    <strong> - Texto importante
    <i> - Texto itálico
    <em> - Texto enfatizado
    <mark> - Texto marcado
    <small> - Texto menor
    <del> - Texto excluído
    <ins> - Texto inserido
    <sub> - Texto subscrito
    <sup> - Texto de sobrecrito
    ```
    
- **comentar no html**
    
    ```html
    <!-- This is a comment -->
    
    <p>This is a paragraph.</p>
    
    <!-- Remember to add more information here -->
    ```
    
- 

---

## **Tags HTML estruturais**

- **header**
    
    Essas tags definem um cabeçalho. Portanto, todo conteúdo que estiver dentro dela faz parte de um cabeçalho, podendo ser utilizado dentro de outras sessões. Não confundir com as tags <head>;
    
- **main**
    
    Essas tags representam o conteúdo principal do seu corpo, ou seja, o conteúdo relacionado diretamente com o tópico central da página ou com a funcionalidade central da aplicação;
    
- **footer**
    
    ssas tags definem um rodapé para a página, geralmente utilizadas no final da página;
    
- **section**
    
    Essas tags definem uma sessão para sua página;
    
- **article**
    
    Essas tags definem um artigo da sua página. Nesse sentido, são utilizadas para separar o conteúdo da sua página. Muito utilizado principalmente por blogs ou páginas de conteúdo;
    
- **aside**
    
    Essas tags representam uma seção de uma página cujo conteúdo é tangencialmente relacionado ao conteúdo do seu entorno, que poderia ser considerado separado do conteúdo;
    
- **nav**
    
    Essa tag define um conteúdo de navegação. Portanto, é muito utilizado em conjunto com listas e na criação de menus;
    
- **div**
    
    Define uma divisão da página. Desta forma, funciona como um container para conteúdo de fluxo. Uma vez que não possui um valor semântico, é muito utilizado para organizar melhor o conteúdo. Anteriormente ao HTML5, era utilizado no lugar das categorias acima.
    

---

- **adicionar videos & audio**
    
    ```html
    <video controls>
      <source src="video.mp4" type="video/mp4">
      <source src="video.ogg" type="video/ogg">
      Seu navegador não possui suporte para Vídeos.
    </video>
    
    <audio controls>
      <source src="musica.ogg" type="audio/ogg">
      <source src="musica.mp3" type="audio/mpeg">
      Seu navegador não possui suporte para áudio.
    </audio>
    ```
    
- **incluir recursos de outras pag**
    
    ```html
    <iframe src="https://www.homehost.com.br">
      <p>Seu navegador não possui suporte para iFrames.</p>
    </iframe>
    ```
