<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nutrição Inteligente Pro | Portal Completo</title>
    <link rel="stylesheet" href="style.css">
    <style>
        :root { --verde: #2e7d32; --azul: #0277bd; --branco: #ffffff; }
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; line-height: 1.6; color: #333; }
        header { background: linear-gradient(135deg, var(--verde), var(--azul)); color: white; padding: 40px 20px; text-align: center; }
        nav { background: #f4f4f4; padding: 10px; position: sticky; top: 0; z-index: 1000; border-bottom: 2px solid #ddd; }
        nav ul { list-style: none; display: flex; justify-content: center; gap: 15px; flex-wrap: wrap; padding: 0; margin: 0; }
        nav a { text-decoration: none; color: #444; font-weight: bold; font-size: 14px; transition: 0.3s; }
        nav a:hover { color: var(--verde); }
        .container { max-width: 1100px; margin: auto; padding: 20px; }
        .grid-artigos { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; margin-top: 30px; }
        .card { border: 1px solid #eee; border-radius: 12px; padding: 20px; background: white; box-shadow: 0 4px 6px rgba(0,0,0,0.05); transition: 0.3s; }
        .card:hover { transform: translateY(-5px); box-shadow: 0 10px 20px rgba(0,0,0,0.1); }
        .btn { display: inline-block; background: var(--verde); color: white; padding: 10px 20px; border-radius: 5px; text-decoration: none; margin-top: 15px; }
        footer { background: #333; color: white; text-align: center; padding: 40px 20px; margin-top: 60px; }
    </style>
</head>
<body>

<header>
    <h1>Nutrição Inteligente Pro</h1>
    <p>Tecnologia e Saúde Aplicadas à Sua Vida</p>
</header>

<nav>
    <ul>
        <li><a href="#home">Início</a></li>
        <li><a href="#comer">O que Comer</a></li>
        <li><a href="#evitar">O que Evitar</a></li>
        <li><a href="#agua">Hidratação</a></li>
        <li><a href="#plano">Plano Diário</a></li>
        <li><a href="#mente">Mente & Foco</a></li>
        <li><a href="#massa">Ganho de Massa</a></li>
        <li><a href="#contato">Contato</a></li>
    </ul>
</nav>

<div class="container">
    <section id="home" style="text-align: center; padding: 40px 0;">
        <h2>Sua Saúde é o seu Melhor Ativo</h2>
        <p style="font-size: 1.2rem; color: #666;">"Investir na sua alimentação é como otimizar o código do seu sistema mais importante: você mesmo."</p>
    </section>

    <div class="grid-artigos">
        <div class="card" id="comer">
            <h3>🍎 O Que Comer</h3>
            <p>Proteínas de alta qualidade, gorduras boas e carboidratos complexos. Saiba como escolher frutas e verduras frescas.</p>
            <a href="#" class="btn">Ler Guia Completo</a>
        </div>

        <div class="card" id="evitar">
            <h3>🚫 O Que Evitar</h3>
            <p>Fuja dos ultraprocessados, açúcares ocultos e gorduras trans que diminuem sua performance mental e física.</p>
            <a href="#" class="btn">Ver Lista Proibida</a>
        </div>

        <div class="card" id="agua">
            <h3>💧 Hidratação Inteligente</h3>
            <p>O cálculo ideal: <strong>35ml x seu peso</strong>. Descubra os benefícios de beber água na hora certa.</p>
            <a href="#" class="btn">Calcular Minha Água</a>
        </div>

        <div class="card" id="plano">
            <h3>📅 Plano Alimentar Diário</h3>
            <p>Ideias para Café da manhã, Almoço e Jantar equilibrados para manter a energia o dia todo.</p>
            <a href="#" class="btn">Ver Cardápio</a>
        </div>

        <div class="card" id="mente">
            <h3>🧠 Alimentação e Mente</h3>
            <p>Como o que você come afeta seu foco, memória e prevenção de estresse.</p>
            <a href="#" class="btn">Saúde Mental</a>
        </div>

        <div class="card" id="massa">
            <h3>🏋️ Ganho de Massa</h3>
            <p>Rotina alimentar para quem busca força e vitalidade sem abrir mão da saúde.</p>
            <a href="#" class="btn">Ver Treino e Dieta</a>
        </div>
    </div>
</div>

<footer id="contato">
    <p><strong>Nutrição Inteligente Pro</strong></p>
    <p>Responsável Técnico: <strong>Uanderson Martins</strong> (Analista de Sistemas)</p>
    <p>WhatsApp: <a href="https://wa.me/5521992444504" style="color: #4caf50;">(21) 99244-4504</a> | Email: andubryranrj@hotmail.com</p>
    <p style="font-size: 0.8rem; opacity: 0.7;">Este site é educativo. Consulte sempre um nutricionista.</p>
    <div style="margin-top: 20px;">
        <a href="politica.html" style="color: #aaa; text-decoration: none;">Política de Privacidade</a>
    </div>
</footer>
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>O Que Comer | Nutrição Inteligente Pro</title>
    <link rel="stylesheet" href="style.css">
</head>
<body style="font-family: sans-serif; line-height: 1.6; margin: 0;">
    <header style="background: #2e7d32; color: white; padding: 20px; text-align: center;">
        <h1>O Que Comer para ter Saúde</h1>
    </header>
    <main style="max-width: 800px; margin: 20px auto; padding: 20px;">
        <h2>🍎 Alimentos que Transformam seu Sistema</h2>
        <p>Para um funcionamento perfeito do corpo, priorize:</p>
        <ul>
            <li><strong>Frutas:</strong> Maçã, banana e frutas cítricas para imunidade.</li>
            <li><strong>Proteínas:</strong> Ovos, peixes e frango grelhado.</li>
            <li><strong>Carboidratos:</strong> Batata doce, aveia e arroz integral.</li>
        </ul>
        <a href="index.html" style="color: #2e7d32; font-weight: bold;">← Voltar ao Início</a>
    </main>
</body>
</html>
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Plano Alimentar | Nutrição Inteligente Pro</title>
    <link rel="stylesheet" href="style.css">
</head>
<body style="font-family: sans-serif; line-height: 1.6; margin: 0;">
    <header style="background: #2e7d32; color: white; padding: 20px; text-align: center;">
        <h1>📅 Sugestão de Rotina Diária</h1>
    </header>
    <main style="max-width: 800px; margin: 20px auto; padding: 20px;">
        <h3>Café da Manhã</h3>
        <p>Ovos mexidos com 1 fatia de pão integral e café sem açúcar.</p>
        <h3>Almoço</h3>
        <p>Grande porção de salada, 1 concha de feijão, arroz integral e uma fonte de proteína.</p>
        <h3>Jantar</h3>
        <p>Sopa de legumes ou grelhado leve para não pesar no sono.</p>
        <a href="index.html" style="color: #2e7d32; font-weight: bold;">← Voltar</a>
    </main>
</body>
</html>
</body>
</html>
