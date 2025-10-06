<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vozes que Curam - Autoajuda para Ansiedade e Depressão</title>
    <style>
        /* CSS para um design moderno e atrativo para jovens: cores suaves (azul calmo, verde esperança), fontes sans-serif, responsivo */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff; /* Azul claro suave */
            color: #333;
            line-height: 1.6;
        }
        header {
            background: linear-gradient(135deg, #4a90e2, #50c878); /* Gradiente azul-verde para atrair atenção */
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }
        nav {
            background-color: #333;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #50c878;
        }
        section {
            padding: 40px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        #home {
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="grain" width="100" height="100" patternUnits="userSpaceOnUse"><circle cx="25" cy="25" r="1" fill="%23ffffff" opacity="0.1"/><circle cx="75" cy="75" r="1" fill="%23ffffff" opacity="0.1"/></pattern></defs><rect width="100" height="100" fill="%23f0f8ff" opacity="0.5"/><rect width="100" height="100" fill="url(%23grain)"/></svg>') repeat; /* Textura sutil para dinamismo */
            text-align: center;
        }
        #home h2 {
            color: #4a90e2;
            font-size: 2em;
        }
        .call-to-action {
            background: #50c878;
            color: white;
            padding: 15px;
            border-radius: 10px;
            margin: 20px 0;
            font-size: 1.2em;
            cursor: pointer;
            transition: transform 0.3s;
        }
        .call-to-action:hover {
            transform: scale(1.05);
        }
        #resources {
            background-color: #e8f5e8; /* Verde claro */
        }
        .resource-card {
            background: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            display: flex;
            align-items: center;
        }
        .resource-card h3 {
            color: #4a90e2;
        }
        .phone-highlight {
            font-size: 1.5em;
            font-weight: bold;
            color: #ff6b6b; /* Vermelho para destaque */
        }
        #tips {
            background-color: #fff3cd; /* Amarelo suave para dicas */
        }
        .tip {
            background: white;
            padding: 15px;
            margin: 15px 0;
            border-left: 5px solid #50c878;
            border-radius: 5px;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
        }
        #testimonials {
            background-color: #f8f9fa;
        }
        .testimonial {
            background: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            position: relative;
        }
        .testimonial::before {
            content: '"';
            font-size: 4em;
            color: #50c878;
            position: absolute;
            top: -10px;
            left: 20px;
            opacity: 0.5;
        }
        .testimonial-author {
            font-style: italic;
            color: #666;
            text-align: right;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
        /* Responsivo para mobile (essencial para jovens) */
        @media (max-width: 768px) {
            header h1 { font-size: 2em; }
            nav a { display: block; margin: 5px 0; }
            .resource-card { flex-direction: column; text-align: center; }
        }
        /* Animação simples para engajamento */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        section { animation: fadeIn 1s ease-out; }
    </style>
</head>
<body>

    <header>
        <h1>Vozes que Curam</h1>
        <p>Seu espaço seguro para superar ansiedade e depressão. Você não está sozinho!</p>
    </header>

    <nav>
        <a href="#home">Início</a>
        <a href="#resources">Recursos</a>
        <a href="#tips">Dicas</a>
        <a href="#testimonials">Depoimentos</a>
        <a href="#contact">Contato</a>
    </nav>

    <section id="home">
        <h2>Bem-vindo ao Vozes que Curam</h2>
        <p>Se você é adolescente ou jovem e está lidando com ansiedade ou depressão, saiba que há esperança. Este site foi criado para te ajudar a encontrar voz interior que cura. Com dicas práticas, recursos acessíveis e histórias reais, estamos aqui para te apoiar no dia a dia.</p>
        <div class="call-to-action" onclick="scrollToSection('resources')">
            Precisa de ajuda agora? Ligue 188 – Linha de Autoajuda Gratuita!
        </div>
        <img src="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' width='300' height='200' viewBox='0 0 300 200'><rect width='300' height='200' fill='%234a90e2' rx='10'/><text x='150' y='100' text-anchor='middle' fill='white' font-size='24' font-family='Arial'>Ilustração: Mãos se unindo em apoio</text></svg>" alt="Ilustração de apoio" style="max-width:100%; border-radius:10px;">
        <!-- Placeholder para imagem; em um site real, use uma imagem real de mãos ou corações -->
    </section>

    <section id="resources">
        <h2>Recursos de Apoio</h2>
        <p>Aqui você encontra ferramentas para lidar com o que está sentindo. Lembre-se: buscar ajuda é um ato de coragem!</p>
        
        <div class="resource-card">
            <div>
                <h3>Linha de Autoajuda</h3>
                <p class="phone-highlight">Ligue para 188</p>
                <p>Atendimento 24h gratuito e confidencial para crises de ansiedade e depressão. Disponível em todo o Brasil.</p>
            </div>
        </div>
        
        <div class="resource-card">
            <h3>Apps Recomendados</h3>
            <p>Experimente apps como Calm ou Headspace para meditações guiadas. Gratuitos para iniciantes!</p>
        </div>
        
        <div class="resource-card">
            <h3>Comunidades Online</h3>
            <p>Junte-se a fóruns como o Reddit (r/ansiedade) ou grupos no Discord para jovens como você. Compartilhe sem julgamento.</p>
        </div>
        
        <div class="resource-card">
            <h3>Profissionais</h3>
            <p>Procure um psicólogo pelo SUS ou apps como Vittude. Primeira sessão muitas vezes é gratuita.</p>
        </div>
    </section>

    <section id="tips">
        <h2>Dicas Práticas para o Dia a Dia</h2>
        <p>Comece pequeno. Essas dicas são baseadas em técnicas comprovadas para gerenciar ansiedade e depressão.</p>
        
        <div class="tip">
            <h3>Respiração 4-7-8</h3>
            <p>Inspire por 4 segundos, segure por 7, expire por 8. Faça isso 4 vezes ao dia para acalmar a mente ansiosa.</p>
        </div>
        
        <div class="tip">
            <h3>Diário de Gratidão</h3>
            <p>Escreva 3 coisas boas que aconteceram hoje. Ajuda a combater pensamentos depressivos, mesmo nos dias ruins.</p>
        </div>
        
        <div class="tip">
            <h3>Movimento Diário</h3>
            <p>Caminhe 10 minutos ouvindo sua playlist favorita. Exercício libera endorfinas, o "hormônio da felicidade".</p>
        </div>
        
        <div class="tip">
            <h3>Limites nas Redes Sociais</h3>
            <p>Defina um timer de 30 min/dia. Redes podem piorar a ansiedade – foque no real.</p>
        </div>
        
        <div class="tip">
            <h3>Converse com Alguém</h3>
            <p>Fale com um amigo ou familiar. Se não souber como, comece com "Estou me sentindo assim...".</p>
        </div>
    </section>

    <section id="testimonials">
        <h2>O Que as Pessoas Estão Dizendo</h2>
        <p>Ouça as vozes que já se curaram um pouco mais. Esses depoimentos são inspirados em histórias reais (anônimos para privacidade).</p>
        
        <div class="testimonial">
            <p>Esse site me ajudou a entender que minha ansiedade não me define. As dicas de respiração mudaram meus ataques de pânico!</p>
            <span class="testimonial-author">- Ana, 17 anos</span>
        </div>
        
        <div class="testimonial">
            <p>Eu me sentia tão sozinho com a depressão, mas ler os depoimentos me deu forças para ligar no 188. Obrigado por ser um espaço jovem e sem julgamentos.</p>
            <span class="testimonial-author">- João, 20 anos</span>
        </div>
        
        <div class="testimonial">
            <p>As dicas práticas são reais, não aquela coisa chata de autoajuda. Me sinto mais leve agora, e o design é super legal para a gente da minha idade.</p>
            <span class="testimonial-author">- Maria, 16 anos</span>
        </div>
        
        <div class="testimonial">
            <p>Primeira vez que vejo um site que fala direto com adolescentes. Me incentivou a buscar ajuda profissional. Vozes que Curam é vida!</p>
            <span class="testimonial-author">- Pedro, 19 anos</span>
        </div>
    </section>

    <section id="contact">
        <h2>Entre em Contato</h2>
        <p>Quer compartilhar sua história ou sugerir algo? Envie uma mensagem. Seu feedback nos ajuda a crescer!</p>
        <form style="max-width: 600px; margin: 0 auto;">
            <label for="name">Nome:</label><br>
            <input type="text" id="name" name="name" style="width:100%; padding:10px; margin:5px 0; border-radius:5px; border:1px solid #ccc;"><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" style="width:100%; padding:10px; margin:5px 0; border-radius:5px; border:1px solid #ccc;"><br>
            <label for="message">Mensagem:</label><br>
            <textarea id="message" name="message" rows="5" style="width:100%; padding:10px; margin:5px 0; border-radius:5px; border:1px solid #ccc;"></textarea><br>
            <button type="submit" style="background:#50c878; color:white; padding:10px 20px; border:none; border-radius:5px; cursor:pointer;">Enviar</button>
        </form>
        <p style="text-align:center; margin-top:20px;"><em>Nota: Este formulário é simulado. Em um site real, integre com um backend como PHP ou Formspree.</em></p>
    </section>

    <footer>
        <p>&copy; 2023 Vozes que Curam. Todos os direitos reservados. | Se precisar de ajuda urgente, ligue 188 ou 192 (SAMU). | Desenvolvido com carinho para jovens como você.</p>
    </footer>

    <script>
        // JavaScript simples para interatividade: scroll suave e alerta no formulário
        function scrollToSection(id) {
            document.getElementById(id).scrollIntoView({ behavior: 'smooth' });
        }
        
        // Simular envio de formulário
        document.querySelector('form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Mensagem enviada! Obrigado por compartilhar. Vamos responder em breve.');
        });
        
        // Adicionar scroll suave para links de navegação
        document.querySelectorAll('nav a').forEach(link => {
            link.addEventListener('click', function(e) {
                e.preventDefault();
                const targetId = this.getAttribute('href').substring(1);
                scrollToSection(targetId);
            });
        });
    </script>

</body>
</html>
