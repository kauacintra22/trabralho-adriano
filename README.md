<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Início – Tech Fácil</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
 
<header>
    <h1>Tech Fácil</h1>
    <nav>
        <a href="index.html" class="active">Início</a>
        <a href="sobre.html">Sobre</a>
        <a href="contato.html">Contato</a>
    </nav>
</header>
 
<main>
    <div class="badge">Projeto Escolar 2026</div>
    <h2>Bem-vindo ao <span class="destaque">Tech Fácil</span></h2>
    <p class="lead">Este site foi criado para ajudar iniciantes a entender tecnologia de forma simples e acessível.</p>
    <a href="sobre.html" class="btn">Saiba mais</a>
 
    <div class="cards">
        <div class="card">
            <div class="icon">💡</div>
            <h3>Simples</h3>
            <p>Conteúdo pensado para quem está começando.</p>
        </div>
        <div class="card">
            <div class="icon">📚</div>
            <h3>Educativo</h3>
            <p>Aprenda conceitos básicos de tecnologia.</p>
        </div>
        <div class="card">
            <div class="icon">🚀</div>
            <h3>Prático</h3>
            <p>Exemplos reais do dia a dia.</p>
        </div>
    </div>
</main>
 
<footer>
    <p>© 2026 — Projeto Escolar · Tech Fácil</p>
</footer>
 
</body>
</html>
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sobre – Tech Fácil</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
 
<header>
    <h1>Tech Fácil</h1>
    <nav>
        <a href="index.html">Início</a>
        <a href="sobre.html" class="active">Sobre</a>
        <a href="contato.html">Contato</a>
    </nav>
</header>
 
<main>
    <h2>Sobre o <span class="destaque">Projeto</span></h2>
    <p class="lead">Conheça quem somos e o que queremos alcançar.</p>
 
    <div class="info-grid">
        <div class="info-box">
            <h4>Quem somos</h4>
            <p>Somos alunos desenvolvendo um site estático como atividade escolar.</p>
        </div>
        <div class="info-box">
            <h4>Objetivo</h4>
            <p>Ensinar conceitos básicos de tecnologia de forma acessível a todos.</p>
        </div>
        <div class="info-box">
            <h4>Tecnologias</h4>
            <p>HTML, CSS e JavaScript — as bases da web moderna.</p>
        </div>
        <div class="info-box">
            <h4>Público-alvo</h4>
            <p>Iniciantes que querem aprender tecnologia do zero.</p>
        </div>
    </div>
</main>
 
<footer>
    <p>© 2026 — Projeto Escolar · Tech Fácil</p>
</footer>
 
</body>
</html>
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contato – Tech Fácil</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
 
<header>
    <h1>Tech Fácil</h1>
    <nav>
        <a href="index.html">Início</a>
        <a href="sobre.html">Sobre</a>
        <a href="contato.html" class="active">Contato</a>
    </nav>
</header>
 
<main>
    <h2>Fale com <span class="destaque">a gente</span></h2>
    <p class="lead">Manda sua mensagem, vai ser um prazer responder!</p>
 
    <div class="form-box">
        <form>
            <label for="nome">Nome</label>
            <input type="text" id="nome" name="nome" placeholder="Seu nome">
 
            <label for="email">Email</label>
            <input type="email" id="email" name="email" placeholder="seu@email.com">
 
            <label for="mensagem">Mensagem</label>
            <textarea id="mensagem" name="mensagem" placeholder="Escreva sua mensagem..."></textarea>
 
            <button type="submit">Enviar mensagem</button>
        </form>
    </div>
</main>
 
<footer>
    <p>© 2026 — Projeto Escolar · Tech Fácil</p>
</footer>
 
</body>
</html>
@import url('https://fonts.googleapis.com/css2?family=Sora:wght@400;600;700&family=DM+Sans:wght@400;500&display=swap');
 
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
 
body {
    font-family: 'DM Sans', sans-serif;
    background: #0f1117;
    color: #e8e9f0;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
}
 
/* ── HEADER ── */
header {
    background: #1a1d2e;
    border-bottom: 1px solid #2a2d3e;
    padding: 18px 40px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    position: sticky;
    top: 0;
    z-index: 100;
}
 
header h1 {
    font-family: 'Sora', sans-serif;
    font-size: 22px;
    font-weight: 700;
    background: linear-gradient(90deg, #7c6df0, #a78bfa);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}
 
/* ── NAV ── */
nav {
    display: flex;
    gap: 4px;
}
 
nav a {
    padding: 7px 18px;
    border-radius: 8px;
    font-size: 14px;
    font-weight: 500;
    color: #9ca3af;
    text-decoration: none;
    transition: background 0.2s, color 0.2s;
}
 
nav a:hover {
    background: #1e2030;
    color: #e8e9f0;
}
 
nav a.active {
    background: #2d2060;
    color: #a78bfa;
}
 
/* ── MAIN ── */
main {
    padding: 56px 40px 100px;
    flex: 1;
}
 
/* ── TIPOGRAFIA ── */
.badge {
    display: inline-block;
    background: #1e1b40;
    color: #a78bfa;
    font-size: 12px;
    font-weight: 500;
    padding: 4px 14px;
    border-radius: 20px;
    border: 1px solid #3d2f8a;
    margin-bottom: 18px;
}
 
h2 {
    font-family: 'Sora', sans-serif;
    font-size: 34px;
    font-weight: 700;
    line-height: 1.2;
    margin-bottom: 14px;
}
 
.destaque {
    background: linear-gradient(90deg, #7c6df0, #c084fc);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}
 
.lead {
    font-size: 16px;
    color: #9ca3af;
    line-height: 1.7;
    max-width: 540px;
    margin-bottom: 28px;
}
 
/* ── BOTÃO ── */
.btn {
    display: inline-block;
    background: linear-gradient(135deg, #6d55e8, #8b5cf6);
    color: white;
    padding: 12px 28px;
    border-radius: 10px;
    font-size: 15px;
    font-weight: 600;
    text-decoration: none;
    transition: opacity 0.2s;
    margin-bottom: 48px;
}
 
.btn:hover {
    opacity: 0.88;
}
 
/* ── CARDS (Início) ── */
.cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 16px;
}
 
.card {
    background: #1a1d2e;
    border: 1px solid #2a2d3e;
    border-radius: 14px;
    padding: 24px 20px;
    transition: border-color 0.2s;
}
 
.card:hover {
    border-color: #4c3d9a;
}
 
.icon {
    font-size: 28px;
    margin-bottom: 12px;
}
 
.card h3 {
    font-family: 'Sora', sans-serif;
    font-size: 16px;
    font-weight: 600;
    color: #e8e9f0;
    margin-bottom: 8px;
}
 
.card p {
    font-size: 14px;
    color: #6b7280;
    line-height: 1.5;
}
 
/* ── INFO GRID (Sobre) ── */
.info-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 16px;
    margin-top: 8px;
}
 
.info-box {
    background: #1a1d2e;
    border: 1px solid #2a2d3e;
    border-radius: 14px;
    padding: 22px 20px;
}
 
.info-box h4 {
    font-family: 'Sora', sans-serif;
    font-size: 11px;
    font-weight: 600;
    color: #a78bfa;
    text-transform: uppercase;
    letter-spacing: 0.06em;
    margin-bottom: 10px;
}
 
.info-box p {
    font-size: 14px;
    color: #d1d5db;
    line-height: 1.6;
}
 
/* ── FORMULÁRIO (Contato) ── */
.form-box {
    background: #1a1d2e;
    border: 1px solid #2a2d3e;
    border-radius: 16px;
    padding: 32px;
    max-width: 480px;
}
 
form label {
    display: block;
    font-size: 13px;
    font-weight: 500;
    color: #9ca3af;
    margin-bottom: 6px;
    margin-top: 18px;
}
 
form label:first-child {
    margin-top: 0;
}
 
form input,
form textarea {
    width: 100%;
    background: #0f1117;
    border: 1px solid #2a2d3e;
    border-radius: 8px;
    padding: 10px 14px;
    color: #e8e9f0;
    font-family: 'DM Sans', sans-serif;
    font-size: 14px;
    outline: none;
    transition: border-color 0.2s;
}
 
form input:focus,
form textarea:focus {
    border-color: #6d55e8;
}
 
form textarea {
    height: 110px;
    resize: vertical;
}
 
form button {
    margin-top: 22px;
    width: 100%;
    background: linear-gradient(135deg, #6d55e8, #8b5cf6);
    color: white;
    padding: 12px;
    border-radius: 10px;
    font-family: 'DM Sans', sans-serif;
    font-size: 15px;
    font-weight: 600;
    border: none;
    cursor: pointer;
    transition: opacity 0.2s;
}
 
form button:hover {
    opacity: 0.88;
}
 
/* ── FOOTER ── */
footer {
    background: #080a10;
    border-top: 1px solid #1e2030;
    padding: 16px 40px;
    text-align: center;
    font-size: 13px;
    color: #4b5563;
}
