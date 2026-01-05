<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Letícia Alcântara | Fisioterapeuta</title>

<style>
html {
    scroll-behavior: smooth;
}

* {
    box-sizing: border-box;
}

body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    background-color: #f4f6f8;
    color: #333;
    padding-top: 130px;
    overflow-x: hidden;
}

/* ===== BARRA SUPERIOR ===== */
.top-bar {
    background-color: #0f766e;
    color: #fff;
    padding: 15px 20px;
    position: fixed;
    top: 0;
    width: 100%;
    z-index: 1002;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

/* ===== MENU ===== */
.nav-bar {
    background-color: #115e59;
    position: fixed;
    top: 60px;
    width: 100%;
    z-index: 1001;
}

.nav-bar nav {
    display: flex;
    justify-content: center;
    gap: 30px;
}

.nav-bar nav a {
    color: #fff;
    text-decoration: none;
    padding: 12px 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.nav-bar nav a:hover {
    opacity: 0.8;
}

/* ===== SEÇÕES ===== */
section {
    padding: 60px 20px;
    max-width: 1100px;
    margin: auto;
    scroll-margin-top: 150px;
    transition: all 0.4s ease;
}

.hero {
    background: linear-gradient(to right, #0f766e, #14b8a6);
    color: white;
    padding: 80px 20px;
    text-align: center;
}

/* ===== BOTÃO ===== */
.btn {
    background-color: #fff;
    color: #0f766e;
    padding: 15px 30px;
    border-radius: 30px;
    text-decoration: none;
    font-weight: bold;
    display: inline-block;
}

/* ===== GRID ===== */
.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
}

/* ===== CARD ===== */
.card {
    background-color: #fff;
    padding: 30px;
    border-radius: 12px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    text-align: center;
    transition: transform 0.3s ease;
}

.card:hover {
    transform: translateY(-5px);
}

/* ===== FOTO SOBRE ===== */
.foto-sobre {
    display: flex;
    justify-content: center;
    margin: 30px 0;
}

.foto-sobre img {
    width: 180px;
    height: 180px;
    object-fit: cover;
    border-radius: 50%;
}

/* ===== CARROSSEL ===== */
.carrossel img {
    width: 100%;
    max-width: 350px;
    border-radius: 12px;
}

/* ===== BUSCA ===== */
.busca-container {
    max-width: 600px;
    margin: 0 auto 40px;
    text-align: center;
}

.busca-container input {
    width: 100%;
    padding: 15px;
    border-radius: 30px;
    border: 1px solid #ccc;
    font-size: 16px;
}

/* ===== SUPORTE ===== */
.suporte {
    background-color: #ffffff;
    border-radius: 12px;
    padding: 40px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

.suporte h3 {
    margin-bottom: 20px;
}

.suporte a {
    display: inline-block;
    margin: 10px;
}

/* ===== TEMA ESCURO ===== */
body.dark {
    background-color: #0f172a;
    color: #e5e7eb;
}

body.dark .top-bar,
body.dark .nav-bar,
body.dark footer,
body.dark .card,
body.dark .suporte {
    background-color: #020617;
    color: #e5e7eb;
}

/* ===== FOOTER ===== */
footer {
    background-color: #0f766e;
    color: #fff;
    text-align: center;
    padding: 20px;
}
</style>
</head>

<body>

<div class="top-bar">
    <h2>Letícia Alcântara | Fisioterapeuta</h2>
    <span id="toggleTheme" style="font-size:24px;cursor:pointer;">☀️</span>
</div>

<div class="nav-bar">
    <nav>
        <a href="#sobre">👩‍⚕️<span>Sobre</span></a>
        <a href="#servicos">🏥<span>Serviços</span></a>
        <a href="#contato">📞<span>Contato</span></a>
        <a href="#suporte">🛠️<span>Suporte</span></a>
    </nav>
</div>

<section class="hero">
    <h1>Cuidado, movimento e qualidade de vida</h1>
    <p>Atendimento fisioterapêutico humanizado e personalizado</p>
    <a class="btn" href="https://wa.me/5581986321182" target="_blank">Agendar pelo WhatsApp</a>
</section>

<section>
    <h2>Pesquisar serviços</h2>
    <div class="busca-container">
        <input type="text" id="busca" placeholder="Digite o nome do serviço...">
    </div>
</section>

<section id="servicos">
    <h2>Serviços</h2>
    <div class="grid" id="listaServicos">
        <div class="card">Fisioterapia Ortopédica</div>
        <div class="card">Fisioterapia Pós-operatória</div>
        <div class="card">Reabilitação Funcional</div>
        <div class="card">Atendimento Domiciliar</div>
    </div>
</section>

<section id="suporte">
    <h2>Suporte</h2>
    <div class="suporte">
        <h3>Precisa de ajuda com o app?</h3>
        <p>Entre em contato com nosso suporte técnico pelos canais abaixo:</p>

        <a class="btn" href="https://wa.me/5581985184913" target="_blank">WhatsApp Suporte</a>
        <a class="btn" href="mailto:softwaresaxion@gmail.com">E-mail Suporte</a>

        <p style="margin-top:20px;">
            Utilize o menu para navegar entre as telas.  
            A barra de pesquisa permite localizar serviços rapidamente.  
            O botão de tema alterna entre modo claro e escuro.
        </p>
    </div>
</section>

<footer>
    <p>© 2026 - Fisioterapia Saúde | Todos os direitos reservados</p>
</footer>

<script>
document.getElementById("toggleTheme").onclick = () => {
    document.body.classList.toggle("dark");
};

document.getElementById("busca").addEventListener("input", function() {
    const termo = this.value.toLowerCase();
    document.querySelectorAll("#listaServicos .card").forEach(card => {
        card.style.display = card.innerText.toLowerCase().includes(termo) ? "block" : "none";
    });
});
</script>

</body>
</html>
