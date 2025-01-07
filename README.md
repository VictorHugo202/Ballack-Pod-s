<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vape Store</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">Vape Store</div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Produtos</a></li>
                <li><a href="#">Sobre</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section class="banner">
        <h1>Descubra os Melhores Vapes</h1>
        <p>Os melhores produtos e acessórios de alta qualidade</p>
        <a href="#produtos" class="botao">Ver Produtos</a>
    </section>

    <section id="produtos" class="produtos">
        <div class="produto">
            <img src="images/vape1.jpg" alt="Vape 1">
            <h2>Vape Modelo 1</h2>
            <p>R$ 250,00</p>
            <button>Comprar</button>
        </div>

        <div class="produto">
            <img src="images/vape2.jpg" alt="Vape 2">
            <h2>Vape Modelo 2</h2>
            <p>R$ 320,00</p>
            <button>Comprar</button>
        </div>

        <div class="produto">
            <img src="images/vape3.jpg" alt="Vape 3">
            <h2>Vape Modelo 3</h2>
            <p>R$ 400,00</p>
            <button>Comprar</button>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Vape Store - Todos os direitos reservados</p>
    </footer>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: #222;
    color: white;
}

header .logo {
    font-size: 28px;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 16px;
}

.banner {
    text-align: center;
    padding: 100px 20px;
    background: url('images/banner.jpg') no-repeat center/cover;
    color: white;
}

.banner h1 {
    font-size: 48px;
}

.banner p {
    font-size: 20px;
}

.botao {
    display: inline-block;
    margin-top: 20px;
    padding: 15px 30px;
    background-color: #ff5500;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}

.produtos {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    padding: 40px 20px;
}

.produto {
    border: 1px solid #ddd;
    margin: 15px;
    text-align: center;
    width: 300px;
    padding: 20px;
    background-color: white;
}

.produto img {
    width: 100%;
    height: auto;
}

.produto button {
    background-color: #ff5500;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
    border-radius: 5px;
}

.produto button:hover {
    background-color: #ff3300;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #222;
    color: white;
}