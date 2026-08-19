# meio-ambiente


<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" 
    content="width=device-width, initial-scale=1.0">
    <title>Blog</title>
    <style>
        header{
            background-color: #183c63;
color:#FFFFFF
text-align: center;
max-width: 800px;
margin: 0 auto;
        }
        main {
            background-color: #FFFFFF;
        color: #183c63;
        }
    </style>
</head>
<body>
<h1>Meu Blog tech</h1>
<p>meublog</p>
<p>Vou compartilhar conhecimentos sobre tecnoligia e progrmação</p>

<h2>Meu primeiro post</h2>
Por:Nathaly
<p>Boas-vindas ao meu novo blog! Aqui vou compartilhar dicas de programação e curiosidades da área de tecnoligoia</p>

</body>
</html>
header {
    background-color: #183C63;
    color: #FFFFFF;
    text-align: center;
    max-width: 800px;
    margin: 0 auto;
    padding: 16px;
}

main {ggg
    background-color: #FFFFFF;
    color: #183C63;
    max-width: 800px;
    margin: 0 auto;
    padding: 16px;
}

article {
    display: flex;
}

img {
    width: 80px;
    height: 80px;
}

.artigo-autor {
    font-weight: bold;
}
<link rel="stylesheet" href="style.css">
const botoes = document.querySelectorAll("button");

botoes.forEach(function (botao) {
    let curtiu = false;
    botao.addEventListener("click", botaoClicado);
    function botaoClicado() {
        console.log("fui clicado");
        let texto = botao.querySelector("span");
        if (curtiu === false) {
            texto.textContent++;
            curtiu = true;
        }<script src="script.js"></script> else {
            texto.textContent--;
            curtiu = false;
        }
    }
});
