# estrutura-html-css
Estrutura básica em HTML e CSS com container centralizado e estilização simples
<img width="1358" height="402" alt="{782FDD12-7A67-47B7-BA95-3B4C16F2CA0A}" src="https://github.com/user-attachments/assets/6f6b05b6-a8b1-4deb-bc1b-4da46ababd98" />

Estrutura HTML e CSS

Projeto simples desenvolvido para praticar estruturação em HTML e estilização com CSS.

 Tecnologias utilizadas
- HTML5
- CSS3

Conceitos aplicados
- Estrutura básica de página
- Uso de div container
- Centralização com margin auto
- Estilização interna com <style>

Objetivo
Praticar fundamentos de desenvolvimento web.

Codigo
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML e CSS</title>

    <style>
        #container {
            background: #ccc;
            width: 960px;
            margin: 0 auto;
            padding: 20px;
        }
    </style>

</head>

<body>

    <div id="container">
        <h1>TÍTULO PRINCIPAL</h1>
        <p>TEXTO AO QUAL O TÍTULO SE REFERE</p>

        <ul>
            <li>ITEM 1</li>
            <li>ITEM 2</li>
            <li>ITEM 3</li>
            <li>ITEM 4</li>
        </ul>
    </div>

</body>

</html>
