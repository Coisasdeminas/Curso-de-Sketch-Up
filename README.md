<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curso de SketchUp - Aulas em 3D</title>
    <style>
        /* Estilos Globais e Fundo */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #1a1a1a; /* Fundo escuro */
            color: #ffffff; /* Cor de texto padrão (para o corpo do texto) */
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
            margin: 0;
            min-height: 100vh;
            text-align: center;
        }

        /* Efeito de Texto Dourado e Animado */
        .animated-gold-text {
            /* Define o gradiente "dourado" */
            --gold-gradient: linear-gradient(90deg, #ffd700, #ffcc33, #e6b800, #ffcc33, #ffd700);
            /* Configura o background para usar o gradiente */
            background-image: var(--gold-gradient);
            background-size: 400% 100%; /* Aumenta o tamanho do background para permitir a animação */
            color: transparent; /* Torna o texto transparente */
            -webkit-background-clip: text; /* Clipa o background no formato do texto (para WebKit browsers) */
            background-clip: text; /* Clipa o background no formato do texto */
            font-size: 2.5em; /* Tamanho da fonte para o cabeçalho */
            font-weight: 700;
            margin-bottom: 20px;
            animation: move-bg 5s linear infinite; /* Aplica a animação */
        }

        /* Keyframes para a Animação do Gradiente */
        @keyframes move-bg {
            to {
                background-position: -400% 0; /* Move o gradiente horizontalmente */
            }
        }

        /* Estilo do Botão */
        .cta-button {
            display: inline-block;
            padding: 15px 30px;
            margin-top: 30px;
            background-color: #ffd700; /* Cor de fundo do botão (dourado sólido) */
            color: #1a1a1a; /* Cor do texto no botão */
            text-decoration: none;
            font-size: 1.5em;
            font-weight: bold;
            border-radius: 8px;
            border: 3px solid #e6b800;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(255, 215, 0, 0.5);
        }

        .cta-button:hover {
            background-color: #ffe866;
            transform: scale(1.05);
            box-shadow: 0 6px 20px rgba(255, 215, 0, 0.8);
        }

        /* Estilo para a seção de texto principal */
        .course-details {
            max-width: 800px;
            margin: 20px auto;
            line-height: 1.6;
        }

        .course-details p {
            font-size: 1.1em;
            margin-bottom: 15px;
            /* Efeito de "entrada" de texto animado */
            opacity: 0;
            transform: translateY(20px);
            animation: slide-in 0.8s forwards;
        }

        /* Atrasos para os parágrafos */
        .course-details p:nth-child(2) { animation-delay: 0.5s; }
        .course-details p:nth-child(3) { animation-delay: 1.0s; }
        .course-details p:nth-child(4) { animation-delay: 1.5s; }
        .course-details p:nth-child(5) { animation-delay: 2.0s; }
        .course-details p:nth-child(6) { animation-delay: 2.5s; }
        .course-details p:nth-child(7) { animation-delay: 3.0s; }
        .course-details p:nth-child(8) { animation-delay: 3.5s; }

        /* Keyframes para o "slide-in" de texto */
        @keyframes slide-in {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        /* Estilo para o iframe de vídeo */
        .video-container {
            position: relative;
            width: 100%;
            padding-bottom: 56.25%; /* Proporção 16:9 */
            height: 0;
            overflow: hidden;
            margin-bottom: 30px;
            max-width: 800px;
        }

        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: 0;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.5);
        }

        /* Media Queries para responsividade */
        @media (max-width: 600px) {
            .animated-gold-text {
                font-size: 1.8em;
            }
            .cta-button {
                font-size: 1.2em;
                padding: 12px 25px;
            }
            .course-details p {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>

    <h1 class="animated-gold-text">Quer aprender SketchUp do zero e criar projetos profissionais em 3D?</h1>

    <div class="video-container">
        <iframe 
            src="LINK_DE_INCORPORACAO_DO_YOUTUBE" 
            title="Vídeo de Apresentação do Curso SketchUp" 
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
        </iframe>
    </div>

    <div class="course-details">
        <p>Então esse é o curso que vai transformar suas ideias em maquetes incríveis!</p>
        <p>
            • 🎓 Aulas **100% online**<br>
            • 🧠 Passo a passo **simples e prático**<br>
            • 📜 **Certificado de conclusão**<br>
            • 💻 Acesso **vitalício** — estude no seu ritmo
        </p>
        <p>Se você é arquiteto, designer, engenheiro ou quer entrar no mercado 3D ou se especializar, esse curso é para você!</p>
        <p>🔥 As vagas limitadas estão abertas e o **acesso é imediato**.</p>
        <p>👉 Clique no botão abaixo e **comece agora**:</p>
    </div>

    <a href="https://experttcursos.com.br/sketchup?ref=G95102120U" class="cta-button" target="_blank" rel="noopener noreferrer">
        GARANTA SUA VAGA NO CURSO AGORA!
    </a>

</body>
</html>
