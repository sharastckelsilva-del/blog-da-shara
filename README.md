# blog-da-shara
o blog que sera criado para descobrir novas séries e filmes
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Netflix Blog | Filmes & Séries</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#141414;
    color:#fff;
}

header{
    background:#000;
    padding:20px;
    position:sticky;
    top:0;
}

header h1{
    color:#e50914;
    text-align:center;
    font-size:2.5rem;
}

nav{
    margin-top:15px;
    text-align:center;
}

nav a{
    color:#fff;
    text-decoration:none;
    margin:0 15px;
    transition:.3s;
}

nav a:hover{
    color:#e50914;
}

.hero{
    background:linear-gradient(rgba(0,0,0,.7), rgba(0,0,0,.8)),
    url('https://images.unsplash.com/photo-1489599849927-2ee91cede3ba?auto=format&fit=crop&w=1500&q=80');
    background-size:cover;
    background-position:center;
    text-align:center;
    padding:100px 20px;
}

.hero h2{
    font-size:3rem;
    margin-bottom:20px;
}

.hero p{
    font-size:1.2rem;
}

.container{
    width:90%;
    max-width:1200px;
    margin:40px auto;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:25px;
}

.card{
    background:#1f1f1f;
    border-radius:12px;
    overflow:hidden;
    transition:.3s;
}

.card:hover{
    transform:translateY(-8px);
    box-shadow:0 10px 20px rgba(0,0,0,.5);
}

.card img{
    width:100%;
    height:380px;
    object-fit:cover;
}

.card-content{
    padding:20px;
}

.card h3{
    color:#e50914;
    margin-bottom:10px;
}

.card p{
    color:#ddd;
    line-height:1.6;
}

.btn{
    display:inline-block;
    margin-top:15px;
    background:#e50914;
    color:#fff;
    text-decoration:none;
    padding:10px 20px;
    border-radius:5px;
    transition:.3s;
}

.btn:hover{
    background:#b20710;
}

footer{
    background:#000;
    text-align:center;
    padding:20px;
    margin-top:50px;
    color:#aaa;
}
</style>
</head>
<body>

<header>
    <h1>🎬 Netflix Blog</h1>

    <nav>
        <a href="#">Início</a>
        <a href="#">Filmes</a>
        <a href="#">Séries</a>
        <a href="#">Lançamentos</a>
        <a href="#">Contato</a>
    </nav>
</header>

<section class="hero">
    <h2>Os melhores filmes e séries da Netflix</h2>
    <p>Descubra novidades, críticas e recomendações para sua próxima maratona.</p>
</section>

<div class="container">

    <h2 style="margin-bottom:25px;">🔥 Destaques da Semana</h2>

    <div class="cards">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1517604931442-7e0c8ed2963c?auto=format&fit=crop&w=800&q=80" alt="Filme">
            <div class="card-content">
                <h3>Filmes Imperdíveis</h3>
                <p>
                    Confira uma seleção dos filmes mais assistidos na Netflix,
                    desde ação até suspense e ficção científica.
                </p>
                <a href="#" class="btn">Ler mais</a>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1524985069026-dd778a71c7b4?auto=format&fit=crop&w=800&q=80" alt="Série">
            <div class="card-content">
                <h3>Séries em Alta</h3>
                <p>
                    Conheça as séries que estão dominando o Top 10 da Netflix e
                    descubra por que todo mundo está assistindo.
                </p>
                <a href="#" class="btn">Ler mais</a>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1478720568477-152d9b164e26?auto=format&fit=crop&w=800&q=80" alt="Cinema">
            <div class="card-content">
                <h3>Próximos Lançamentos</h3>
                <p>
                    Veja quais filmes e séries chegam em breve ao catálogo e
                    prepare sua lista para a próxima maratona.
                </p>
                <a href="#" class="btn">Ler mais</a>
            </div>
        </div>

    </div>

</div>

<footer>
    <p>© 2026 Netflix Blog | Projeto desenvolvido em HTML & CSS.</p>
</footer>

</body>
</html>
