<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Mundo da lua</title>

        <style>
    html {
        scroll-behavior: smooth;
    }

    body {
        font-family: Arial, sans-serif;
        background: linear-gradient(135deg, #0f172a, #1e3a8a);
        color: white;
        text-align: center;
        margin: 0;
    }

    section {
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 20px;
    }

    .card {
        max-width: 700px;
        background: rgba(255,255,255,0.1);
        backdrop-filter: blur(10px);
        padding: 30px;
        border-radius: 20px;
        box-shadow: 0 8px 30px rgba(0,0,0,0.3);
        animation: aparecer 1s ease;
    }

    @keyframes aparecer {
        from {
            opacity: 0;
            transform: translateY(30px);
        }
        to {
            opacity: 1;
            transform: translateY(0);
        }
    }

    h1 {
        color: #93c5fd;
        font-size: 3rem;
    }

    h2 {
        color: #bfdbfe;
    }

    p {
        line-height: 1.7;
    }

    .foto {
        width: 150px;
        height: 150px;
        border-radius: 50%;
        border: 4px solid #93c5fd;
        margin-bottom: 20px;
    }

    .botao {
        display: inline-block;
        margin-top: 20px;
        padding: 12px 24px;
        background: #3b82f6;
        color: white;
        text-decoration: none;
        border-radius: 25px;
        transition: 0.3s;
    }

    .botao:hover {
        transform: scale(1.05);
    }

    .skills {
        margin-top: 20px;
    }

    .skill {
        display: inline-block;
        background: rgba(255,255,255,0.15);
        padding: 10px 15px;
        margin: 5px;
        border-radius: 20px;
    }
</style>
        </style>

    </head>
</html>
<body>
    <section>

    <div class="card">

        <img src="FOTOS/download (1).webp" class="foto">

        <h1>Seja bem-vindo ao mundo da lua!</h1>

        <p>
            Meu nome é <strong>Tayla</strong> e este é meu espaço.
        </p>

        <a href="#sobre" class="botao">
            Conheça mais sobre ↓
        </a>

    </div>

</section>

<section id="sobre">

    <div class="card">

        <h2><strong>SOBRE MIM</strong></h2>

        <p>
            Sou estudante de Sistemas de Informação na<br> Universidade Federal do Amazonas - UFAM,
        </p>

        <p>
            Atualmente estou aprendendo programação e construindo
            meus primeiros projetos enquanto desenvolvo meus conhecimentos
            na área de tecnologia.
        </p>

        <p>
            🦅 Corvinal! <br>
            🔧 Entusiasta de Hardware <br>
            💻 Aprendendo Programação <strong>ainda</strong><br>
            🚀 Construindo meu futuro na tecnologia
        </p>

        <div class="skills">
            <span class="skill">HTML</span>
            <span class="skill">LANA DEL REY</span>
            <span class="skill">CSS</span>
            <span class="skill">BTS</span>
            <span class="skill">S.I</span>
            <span class="skill">Hardware</span>
            <span class="skill">THE WEEKND</span>
            <span class="skill">TI</span>
        </div>

    </div>

</section>
    </div>
</body>
