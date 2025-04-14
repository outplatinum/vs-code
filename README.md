<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Meu portfólio</title>
</head>
<body>
    <img src="img/avatar-perfil.png" alt="" srcset="">
    <p>Eu sou Vinicius</p>
    <h1>Eu Aprendo Programação</h1>
    <p>Sou estudante do colégio silvio barros e aprendo programação por meio da matematica 2, usando HTML, CSS e JavaScript. Veja os projetos que já desenvolvi! </p>
    <p>Minhas habilidades</p>
    <div>
            <p>HTML</p>
            <p>CSS</p>
            <p>JavaScript</p>
            <p>Scratch</p>
    </div>
</body>
</html>
/* Código omitido*/

:root {
    --cor-principal: #6E859F;
    --cor-secundaria: #284260;
    --cor-destaque: #C92BFC;
}

body {
    font-family: 'Chakra Petch', sans-serif;
}

h1, h2, h5 {
    color: var(--cor-secundaria);
    font-weight: 700;
}

footer a {
    color: var(--cor-principal)
}

footer a:hover {
    color: var(--cor-destaque);
}
