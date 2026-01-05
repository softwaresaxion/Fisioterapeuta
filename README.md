<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Fisioterapia | Atendimento Humanizado</title>

<style>
    body {
        margin: 0;
        font-family: Arial, Helvetica, sans-serif;
        background-color: #f4f6f8;
        color: #333;
        padding-top: 90px;
    }
    
body {
    overflow-x: hidden;
}

/* BARRA SUPERIOR – NOME DO SITE */
.top-bar {
    background-color: #0f766e;
    color: #fff;
    padding: 15px 20px;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    width: 100%;
    max-width: 100vw;
    z-index: 1001;
    text-align: left;
    box-sizing: border-box;
}

/* BARRA INFERIOR – MENU */
.nav-bar {
    background-color: #115e59;
    position: fixed;
    top: 60px;
    left: 0;
    right: 0;
    width: 100%;
    max-width: 100vw;
    z-index: 1000;
    box-sizing: border-box;
}


    .nav-bar nav {
        display: flex;
        justify-content: center;
        gap: 30px;
        padding:0;
    }

    .nav-bar nav a {
        color: #fff;
        text-decoration: none;
        padding: 50px 20px 4px;
        touch-action: manipulation;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }

    .nav-bar nav a .icone {
        font-size: 26px;
        line-height: 1;
    }

    .nav-bar nav a .texto {
        font-size: 14px;
        margin-top: 6px;
        text-align: center;
    }

    .nav-bar nav a:hover {
        opacity: 0.8;
    }

    section {
        padding: 60px 20px;
        max-width: 1100px;
        margin: auto;
        scroll-margin-top: 150px;
    }

    .hero {
        background: linear-gradient(to right, #0f766e, #14b8a6);
        color: white;
        padding: 80px 20px;
        text-align: center;
    }

    .hero h1 {
        font-size: 36px;
        margin-bottom: 10px;
    }

    .hero p {
        font-size: 18px;
        margin-bottom: 30px;
    }

    .btn {
        background-color: #fff;
        color: #0f766e;
        padding: 15px 30px;
        border-radius: 30px;
        text-decoration: none;
        font-weight: bold;
        display: inline-block;
    }

    section h2 {
        text-align: center;
        margin-bottom: 40px;
        color: #0f766e;
    }

    .grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 30px;
    }

    .card {
        background-color: #fff;
        padding: 30px;
        border-radius: 10px;
        box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        text-align: center;
    }

    .card h3 {
        margin-bottom: 15px;
        color: #0f766e;
    }

    .sobre {
        display: flex;
        flex-wrap: wrap;
        gap: 40px;
        align-items: center;
    }

    .sobre img {
        max-width: 250px;
        border-radius: 12px;
    }

    .contato {
        text-align: center;
    }

    .contato p {
        font-size: 18px;
        margin-bottom: 10px;
    }

    .carrossel {
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 20px;
    }

    .carrossel img {
        width: 100%;
        max-width: 350px;
        border-radius: 12px;
        box-shadow: 0 5px 15px rgba(0,0,0,0.15);
    }

    footer {
        background-color: #0f766e;
        color: #fff;
        text-align: center;
        padding: 20px;
        margin-top: 40px;
    }

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
    box-shadow: 0 6px 18px rgba(0, 0, 0, 0.2);
}
</style>
</head>

<body>

<div class="top-bar">
    <h2>Letícia Alcântara | Fisioterapia</h2>
</div>

<div class="nav-bar">
    <nav>
        <a href="#sobre">
            <span class="icone">👩‍⚕️</span>
            <span class="texto">Sobre</span>
        </a>
        <a href="#servicos">
            <span class="icone">🏥</span>
            <span class="texto">Serviços</span>
        </a>
        <a href="#contato">
            <span class="icone">📞</span>
            <span class="texto">Contato</span>
        </a>
    </nav>
</div>

<section class="hero">
    <h1>Cuidado, movimento e qualidade de vida</h1>
    <p>Atendimento fisioterapêutico humanizado e personalizado</p>
    <a class="btn" href="https://wa.me/5581985184913?text=Olá,%20gostaria%20de%20agendar%20um%20atendimento%20de%20fisioterapia." target="_blank">
        Agendar pelo WhatsApp
    </a>
</section>

<section>
    <h2>Galeria de Atendimento</h2>
    <div class="carrossel">

        <img id="imagemCarrossel" src="https://ortotraumasamaritano.com.br/wp-content/uploads/2023/03/10-Fisioterapia-Ortopedica.jpg" alt="Fisioterapia">

    </div>
</section>

<section id="sobre">
    <h2>Sobre a fisioterapeuta</h2>

    <div class="foto-sobre">
        <img src="https://scontent.cdninstagram.com/v/t51.29350-15/306865982_632671525229479_6977420807138106493_n.webp?stp=dst-jpg_e35_tt6&_nc_cat=108&ig_cache_key=MjkyNzg3MDM0MDkzMzEyNjU0Mw%3D%3D.3-ccb7-5&ccb=7-5&_nc_sid=58cdad&efg=eyJ2ZW5jb2RlX3RhZyI6InhwaWRzLjE0NDB4MTQ0MC5zZHIuZGVmYXVsdF9pbWFnZS5DMyJ9&_nc_ohc=0JATniwozH8Q7kNvwFVXDEv&_nc_oc=Adly1pmx5roICpEyCHJIq__htzo3sqpywK4HqajjSs9YUPYIXC4BtVuYwvxHSSvofvaDyc2ZT-P0qaFlkATfFeir&_nc_zt=23&_nc_ht=scontent.cdninstagram.com&_nc_gid=BU1jIK0VTvzGuVFBrOMjkQ&oh=00_AfprViIOouTjKdKmQJ3jEYWWhp48J-CdPP2xFzutSUGCvQ&oe=695F9D1D" alt="Fisioterapeuta Letícia Alcântara">
    </div>

    <p>
        Sou fisioterapeuta, com <strong>pós-graduação em Fisioterapia Dermatofuncional</strong> e
        <strong>formação completa em Fisioterapia Neurofuncional</strong>, registrada no
        <strong>CREFITO nº 326382-F</strong>.
    </p>

    <p>
        Realizo <strong>atendimento exclusivamente domiciliar</strong>, oferecendo um cuidado
        humanizado, seguro e personalizado, respeitando as necessidades e os objetivos de cada paciente.
    </p>

    <p>
        Meu trabalho é focado em promover <strong>reabilitação, funcionalidade e qualidade de vida</strong>,
        sempre com ética, atenção individual e acompanhamento contínuo.
    </p>
</section>

<section id="servicos">
    <h2>Serviços</h2>
    <div class="grid">
        <div class="card">
            <h3>Fisioterapia Ortopédica</h3>
            <p>Tratamento de dores, lesões musculares e articulares.</p>
        </div>

        <div class="card">
            <h3>Fisioterapia Pós-operatória</h3>
            <p>Recuperação funcional após cirurgias.</p>
        </div>

        <div class="card">
            <h3>Reabilitação Funcional</h3>
            <p>Melhora da mobilidade, força e qualidade de vida.</p>
        </div>

        <div class="card">
            <h3>Atendimento Domiciliar</h3>
            <p>Conforto e segurança no atendimento em casa.</p>
        </div>
    </div>
</section>

<section>
    <h2>Diferenciais</h2>
    <div class="grid">
        <div class="card">✔ Atendimento humanizado</div>
        <div class="card">✔ Avaliação individual</div>
        <div class="card">✔ Profissional qualificada</div>
        <div class="card">✔ Resultados comprovados</div>
    </div>
</section>

<section id="contato" class="contato">
    <h2>Contato</h2>
    <p>📍 Recife - PE</p>
    <p>📞 (81) 98518-4913</p>
    <p>📧 contato@fisioterapiasaude.com</p>
    <br>
    <a class="btn" href="https://wa.me/5581985184913?text=Olá,%20gostaria%20de%20mais%20informações%20sobre%20os%20atendimentos." target="_blank">
        Falar no WhatsApp
    </a>
</section>

<footer>
    <p>© 2026 - Fisioterapia Saúde | Todos os direitos reservados</p>
</footer>

<script>
    const imagens = [
        "https://ortotraumasamaritano.com.br/wp-content/uploads/2023/03/10-Fisioterapia-Ortopedica.jpg",
        "https://estaticos.animaeducacao.com.br/medias/20251103150112/como-e-o-curso-de-fisioterapia.webp",
        "https://estaticos.animaeducacao.com.br/medias/20250514152316/-_Imagem_-_O_que_%C3%A9_Fisioterapia_Entenda_sobre_a_profiss%C3%A3o.webp"
    ];

    let index = 0;

    function avancar() {
        index = (index + 1) % imagens.length;
        document.getElementById("imagemCarrossel").src = imagens[index];
    }

    function voltar() {
        index = (index - 1 + imagens.length) % imagens.length;
        document.getElementById("imagemCarrossel").src = imagens[index];
    }

    setInterval(avancar, 2000);
</script>

</body>
</html>
