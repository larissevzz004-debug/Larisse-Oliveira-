# Larisse-Oliveira-
Meu Site 
/* Importação das fontes */
body {
    font-family: 'Roboto', sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

h1, h2 {
    font-family: 'Playfair Display', serif;
}

/* Cabeçalho */
.main-header {
    background-color: #111;
    color: #fff;
    text-align: center;
    padding: 4rem 0;
    border-bottom: 2px solid #000;
}

.main-header h1 {
    margin: 0;
    font-size: 4rem;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 0.2rem;
}

/* Conteúdo principal */
.container {
    max-width: 800px;
    margin: 2rem auto;
    padding: 0 1rem;
}

/* Posts do blog */
.post {
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 2rem;
    margin-bottom: 2rem;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

.post h2 {
    font-size: 2.5rem;
    color: #111;
    margin-top: 0;
}

.post-meta {
    font-style: italic;
    color: #666;
    margin-bottom: 1rem;
    font-size: 0.9rem;
}

.post p {
    font-size: 1rem;
    color: #333;
}

.read-more {
    display: inline-block;
    color: #000;
    text-decoration: none;
    font-weight: bold;
    border-bottom: 2px solid #000;
    padding-bottom: 3px;
    transition: color 0.3s, border-bottom 0.3s;
}

.read-more:hover {
    color: #555;
    border-bottom-color: #555;
}

/* Rodapé */
.main-footer {
    text-align: center;
    padding: 1rem 0;
    background-color: #111;
    color: #fff;
    margin-top: 2rem;
    border-top: 2px solid #000;
}

.main-footer p {
    margin: 0;
    font-size: 0.8rem;
}

/* Responsividade */
@media (max-width: 600px) {
    .main-header h1 {
        font-size: 2.5rem;
    }

    .post h2 {
        font-size: 2rem;
    }
}
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Blog Pessoal</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400..900;1,400..900&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>

    <header class="main-header">
        <h1>meu-site</h1>
    </header>

    <main class="container">
        <article class="post">
            <h2>Bem-vindo ao meu blog!</h2>
            <p class="post-meta">Publicado em 21 de setembro de 2025</p>
            <p>Este é o primeiro post do meu blog. Aqui, vou compartilhar minhas ideias, experiências e pensamentos sobre diversos temas. Espero que goste da leitura!</p>
            <a href="#" class="read-more">Ler mais</a>
        </article>

        <article class="post">
            <h2>Sobre o estilo minimalista</h2>
            <p class="post-meta">Publicado em 18 de setembro de 2025</p>
            <p>O estilo preto e branco traz uma elegância atemporal, combinando o clássico com um toque moderno. O foco está no conteúdo, na tipografia e no espaço vazio.</p>
            <a href="#" class="read-more">Ler mais</a>
        </article>
    </main>

    <footer class="main-footer">
        <p>&copy; 2025 meu-site. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
