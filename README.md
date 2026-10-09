# <!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Meu Site | Bem-vindo</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #f4f7fb;
            color: #222;
            line-height: 1.6;
        }

        header {
            background: #14213d;
            color: white;
            padding: 20px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 15px;
        }

        header h1 {
            font-size: 26px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
        }

        nav a:hover {
            color: #fca311;
        }

        .hero {
            min-height: 500px;
            padding: 60px 8%;
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 40px;
            flex-wrap: wrap;
            background: linear-gradient(135deg, #eaf2ff, #ffffff);
        }

        .hero-text {
            flex: 1;
            min-width: 260px;
        }

        .hero-text h2 {
            font-size: clamp(32px, 5vw, 48px);
            color: #14213d;
            line-height: 1.2;
            margin-bottom: 20px;
        }

        .hero-text p {
            font-size: 18px;
            margin-bottom: 25px;
        }

        .botao {
            display: inline-block;
            background: #fca311;
            color: #14213d;
            padding: 12px 25px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }

        .botao:hover {
            background: #e89100;
            transform: translateY(-2px);
        }

        .hero img {
            width: 100%;
            max-width: 480px;
            height: 320px;
            object-fit: cover;
            border-radius: 18px;
            box-shadow: 0 10px 30px #14213d25;
        }

        section {
            padding: 60px 8%;
            text-align: center;
        }

        section h2 {
            font-size: 32px;
            color: #14213d;
            margin-bottom: 15px;
        }

        .cards {
            display: flex;
            justify-content: center;
            gap: 25px;
            flex-wrap: wrap;
            margin-top: 35px;
        }

        .card {
            background: white;
            padding: 30px;
            border-radius: 12px;
            flex: 1;
            min-width: 220px;
            max-width: 350px;
            box-shadow: 0 5px 20px #0000000d;
        }

        .card h3 {
            color: #fca311;
            margin-bottom: 12px;
        }

        .contato {
            background: #eaf2ff;
        }

        footer {
            background: #14213d;
            color: white;
            text-align: center;
            padding: 25px;
        }

        @media (max-width: 600px) {
            header {
                flex-direction: column;
            }

            nav a {
                margin: 0 8px;
            }

            .hero {
                padding-top: 45px;
                padding-bottom: 45px;
            }

            .hero img {
                height: 240px;
            }
        }
    </style>
</head>

<body>

    <header>
        <h1>Meu Site</h1>

        <nav>
            <a href="#inicio">Início</a>
            <a href="#sobre">Sobre</a>
            <a href="#servicos">Serviços</a>
            <a href="#contato">Contato</a>
        </nav>
    </header>

    <main>
        <div class="hero" id="inicio">
            <div class="hero-text">
                <h2>Bem-vindo ao meu site!</h2>

                <p>
                    Este é o meu espaço na internet.
                    Um site moderno, bonito e adaptado
                    para celulares e computadores.
                </p>

                <a href="#sobre" class="botao">
                    Conheça mais
                </a>
            </div>

            <img
                src="https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=1000&q=80"
                alt="Escritório moderno com mesas e computadores"
            >
        </div>

        <section id="sobre">
            <h2>Sobre nós</h2>

            <p>
                Aqui você pode escrever sobre você,
                sua empresa, seu projeto ou sua ideia.
                Personalize este espaço como quiser!
            </p>
        </section>

        <section id="servicos">
            <h2>O que oferecemos</h2>

            <div class="cards">
                <div class="card">
                    <h3>Qualidade</h3>
                    <p>Conteúdo feito com atenção aos detalhes.</p>
                </div>

                <div class="card">
                    <h3>Criatividade</h3>
                    <p>Ideias modernas para destacar seu projeto.</p>
                </div>

                <div class="card">
                    <h3>Inovação</h3>
                    <p>Uma experiência simples e agradável.</p>
                </div>
            </div>
        </section>

        <section class="contato" id="contato">
            <h2>Entre em contato</h2>

            <p>
                Quer saber mais? Fale comigo por e-mail.
            </p>

            <br>

            <a
                href="mailto:seuemail@exemplo.com"
                class="botao"
            >
                Enviar e-mail
            </a>
        </section>
    </main>

    <footer>
        <p>© 2026 Meu Site. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
