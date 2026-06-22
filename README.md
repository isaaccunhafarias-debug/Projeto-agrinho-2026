# Projeto-agrinho-2026 
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agrinho 2026 - Desenvolvimento Sustentável</title>
    <style>
        :root {
            --primary-color: #27ae60;
            --secondary-color: #2ecc71;
            --dark-color: #2c3e50;
            --light-bg: #f5f9f6;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: var(--light-bg);
            color: var(--dark-color);
        }

        header {
            background: linear-gradient(135deg, #1e8449, var(--primary-color));
            color: #fff;
            padding: 4rem 1rem;
            text-align: center;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }

        header h1 {
            margin: 0;
            font-size: 3rem;
            letter-spacing: 1px;
        }

        header p {
            font-size: 1.3rem;
            opacity: 0.9;
            margin-top: 10px;
        }

        nav {
            display: flex;
            justify-content: center;
            background: var(--dark-color);
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        nav a {
            color: white;
            padding: 1.2rem 1.5rem;
            text-decoration: none;
            text-transform: uppercase;
            font-weight: bold;
            font-size: 0.9rem;
            transition: background 0.3s ease;
        }

        nav a:hover {
            background-color: var(--primary-color);
        }

        main {
            max-width: 950px;
            margin: 2.5rem auto;
            padding: 0 1rem 5rem 1rem;
        }

        .card {
            background: white;
            padding: 2.5rem;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
            margin-bottom: 2.5rem;
            border-top: 6px solid var(--primary-color);
        }

        h2 {
            color: #1e8449;
            margin-top: 0;
            font-size: 1.8rem;
            border-bottom: 2px solid #eaeded;
            padding-bottom: 0.5rem;
        }

        ul {
            padding-left: 1.5rem;
        }

        li {
            margin-bottom: 0.8rem;
        }

        footer {
            text-align: center;
            padding: 1.5rem;
            background: var(--dark-color);
            color: white;
            font-size: 0.9rem;
            margin-top: 2rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>Agrinho 2026</h1>
        <p>Desenvolvimento Sustentável: O Futuro do Campo e da Cidade</p>
    </header>

    <nav>
        <a href="#introducao">Introdução</a>
        <a href="#pilares">Pilares</a>
        <a href="#reciclagem">Reciclagem</a>
        <a href="#energia">Energia Renovável</a>
        <a href="#praticas">Práticas no Campo</a>
        <a href="#conclusao">Conclusão</a>
    </nav>

    <main>
        <section id="introducao" class="card">
            <h2>O que é Desenvolvimento Sustentável?</h2>
            <p>Desenvolvimento sustentável significa suprir as necessidades do presente sem comprometer a capacidade das próximas gerações de suprir as suas próprias necessidades. No projeto Agrinho, isso se reflete em produzir alimentos de forma inteligente, protegendo a água, o solo e a biodiversidade.</p>
        </section>

        <section id="pilares" class="card">
            <h2>Os Três Pilares da Sustentabilidade</h2>
            <p>Para um projeto ser realmente sustentável, ele precisa equilibrar três fatores fundamentais:</p>
            <ul>
                <li><strong>Ambiental:</strong> Preservação dos recursos naturais, redução da poluição e conservação das florestas.</li>
                <li><strong>Econômico:</strong> Produção financeira eficiente, evitando desperdícios e gerando empregos verdes.</li>
                <li><strong>Social:</strong> Melhoria na qualidade de vida, garantindo saúde, segurança alimentar e educação para todos.</li>
            </ul>
        </section>

        <section id="reciclagem" class="card">
            <h2>Reciclagem e Destinação Correta</h2>
            <p>A reciclagem reduz drasticamente a necessidade de extrair novos recursos da natureza, além de diminuir o acúmulo de lixo nos aterros e oceanos. Separar papéis, plásticos, metais e vidros limpos em nossas casas e escolas é o primeiro passo para garantir que esses materiais voltem para a cadeia produtiva em vez de poluir o planeta.</p>
        </section>

        <section id="energia" class="card">
            <h2>A Importância das Energias Renováveis</h2>
            <p>As energias renováveis são aquelas que vêm de fontes naturais que nunca se esgotam, como o Sol (energia solar), o vento (energia eólica) e a água (energia hídrica). Ao contrário dos combustíveis fósseis (como o petróleo e o carvão), elas são limpas e não emitem os gases poluentes que causam o aquecimento global.</p>
            <p>No cenário do Agrinho, o uso dessas tecnologias no campo — como a instalação de painéis solares para bombear água ou alimentar sistemas de irrigação — mostra como a inovação pode tornar a agricultura muito mais independente, econômica e amiga da natureza.</p>
        </section>

        <section id="praticas" class="card">
            <h2>Práticas Sustentáveis no Dia a Dia</h2>
            <p>Exemplos de ações que unem tecnologia e ecologia para transformar a nossa realidade:</p>
            <ul>
                <li>Uso consciente da água através de sistemas de irrigação gota a gota.</li>
                <li>Uso de biodigestores para transformar resíduos orgânicos em gás e energia.</li>
                <li>Criação de hortas comunitárias e escolares utilizando adubação orgânica.</li>
                <li>Compostagem de resíduos orgânicos para nutrir a terra de forma natural.</li>
            </ul>
        </section>

        <section id="conclusao" class="card">
            <h2>Conclusão: A Importância de Cuidar do Meio Ambiente</h2>
            <p>Cuidar do meio ambiente não é apenas proteger as florestas e os animais; é garantir a nossa própria sobrevivência e qualidade de vida. Cada pequena ação diária — como desligar a torneira, separar o lixo reciclável ou usar a energia de forma consciente — gera um impacto positivo gigante quando feita de forma coletiva.</p>
            <p>O programa Agrinho nos mostra que o campo e a cidade dependem do mesmo equilíbrio ecológico. Praticar o desenvolvimento sustentável é assumir a responsabilidade de construir um futuro onde a tecnologia caminha lado a lado com a preservação ambiental, garantindo um planeta saudável para as próximas gerações.</p>
        </section>
    </main>

    <footer>
        <p>Projeto Agrinho 2026 &copy; Desenvolvimento Sustentável — Escola e Campo Juntos pelo Futuro</p>
    </footer>

</body>
</html>
