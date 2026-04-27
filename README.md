<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nutrição Inteligente Pro | Portal Oficial</title>
    <style>
        :root { --verde: #2e7d32; --azul: #0277bd; --branco: #ffffff; }
        body { font-family: 'Segoe UI', sans-serif; margin: 0; line-height: 1.6; color: #333; background-color: #f4f4f4; }
        header { background: linear-gradient(135deg, var(--verde), var(--azul)); color: white; padding: 40px 20px; text-align: center; }
        nav { background: white; padding: 10px; position: sticky; top: 0; box-shadow: 0 2px 5px rgba(0,0,0,0.1); z-index: 1000; }
        nav ul { list-style: none; display: flex; justify-content: center; gap: 20px; padding: 0; margin: 0; }
        nav a { text-decoration: none; color: var(--verde); font-weight: bold; }
        .container { max-width: 1000px; margin: auto; padding: 20px; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; }
        .card { background: white; border-radius: 12px; padding: 25px; box-shadow: 0 4px 6px rgba(0,0,0,0.05); border-top: 5px solid var(--verde); }
        footer { background: #222; color: white; text-align: center; padding: 40px; margin-top: 50px; }
        .btn { display: inline-block; margin-top: 15px; color: var(--azul); font-weight: bold; text-decoration: none; }
    </style>
</head>
<body>

<header>
    <h1>Nutrição Inteligente Pro</h1>
    <p>Saúde e Tecnologia para o seu Bem-Estar</p>
</header>

<nav>
    <ul>
        <li><a href="#home">Início</a></li>
        <li><a href="#comer">Alimentação</a></li>
        <li><a href="#agua">Hidratação</a></li>
        <li><a href="#plano">Plano Diário</a></li>
        <li><a href="#contato">Contato</a></li>
    </ul>
</nav>

<div class="container">
    <section id="home" style="text-align: center; padding: 30px 0;">
        <h2>Bem-vindo, Uanderson Martins</h2>
        <p>Seu guia profissional de nutrição e hábitos saudáveis.</p>
    </section>

    <div class="grid">
        <div class="card" id="comer">
            <h3>🍎 O que comer e evitar</h3>
            <p>Priorize frutas e proteínas magras. Evite ultraprocessados e excesso de açúcar.</p>
        </div>
        <div class="card" id="agua">
            <h3>💧 Água e Hidratação</h3>
            <p>Beba 35ml por quilo. Para você, o ideal é manter a constância diária.</p>
        </div>
        <div class="card" id="plano">
            <h3>📅 Plano Alimentar</h3>
            <p>Sugestões práticas para café, almoço e jantar equilibrados.</p>
        </div>
    </div>
</div>

<footer id="contato">
    <p><strong>Uanderson Martins - Analista de Sistemas</strong></p>
    <p>WhatsApp: (21) 99244-4504 | Email: andubryranrj@hotmail.com</p>
    <p><small>&copy; 2026 Nutrição Inteligente Pro | <a href="politica.html" style="color: #aaa;">Privacidade</a></small></p>
</footer>

</body>
</html>
