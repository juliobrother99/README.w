# aí professor tô sem Pc então não tô mandando fazer aqui no celular, vou mandar o cód css e HTML aqui kkkkkkkk


<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio de Julio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Julio</h1>
        <p>Desenvolvedor em aprendizado | Entusiasta de tecnologia</p>
    </header>

    <section class="sobre">
        <h2>Sobre Mim</h2>
        <p>Sou um desenvolvedor iniciante estudando HTML, CSS e JavaScript, buscando evoluir no desenvolvimento web.</p>
    </section>

    <section class="projetos">
        <h2>Projetos</h2>
        <ul>
            <li><a href="#">Projeto 1</a></li>
            <li><a href="#">Projeto 2</a></li>
            <li><a href="#">Projeto 3</a></li>
        </ul>
    </section>

    <section class="contato">
        <h2>Contato</h2>
        <p>Email: <a href="mailto:juliobrother99@outlook.com">juliobrother99@outlook.com</a></p>
        <p>GitHub: <a href="https://github.com/seuusuario" target="_blank">github.com/seuusuario</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Julio. Todos os direitos reservados.</p>
    </footer>
</body>
</html>

agora em css 

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    text-align: center;
}

header {
    background-color: #0057b8; /* Azul forte */
    color: white;
    padding: 20px;
}

h1 {
    color: #ffa500; /* Laranja */
}

h2 {
    color: #0057b8; /* Azul */
}

.sobre, .projetos, .contato {
    margin: 20px;
    padding: 20px;
    background: white;
    border-radius: 10px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}

ul {
    list-style: none;
    padding: 0;
}

ul li {
    margin: 10px 0;
}

a {
    text-decoration: none;
    color: #ffa500; /* Laranja */
    font-weight: bold;
}

a:hover {
    color: #ff6600; /* Laranja mais escuro */
}

footer {
    margin-top: 20px;
    background: #0057b8;
    color: white;
    padding: 10px;
}

