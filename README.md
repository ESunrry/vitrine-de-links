index.html

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Erick | Portfólio de Modelos de Sites</title>
  <style>
    :root {
      --bg: #0b0d12;
      --card: #14171f;
      --border: #232838;
      --text: #e8eaf0;
      --muted: #8b93a7;
      --accent: #6c8cff;
      --accent-hover: #8aa3ff;
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
      min-height: 100vh;
    }

    .container {
      width: 100%;
      max-width: 1100px;
      margin: 0 auto;
      padding: 0 20px;
    }

    header {
      text-align: center;
      padding: 72px 0 48px;
    }

    header h1 {
      font-size: clamp(2rem, 6vw, 3.25rem);
      font-weight: 800;
      letter-spacing: -0.02em;
      background: linear-gradient(135deg, #ffffff 30%, var(--accent));
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
    }

    header p {
      margin: 16px auto 0;
      max-width: 520px;
      color: var(--muted);
      font-size: clamp(1rem, 3vw, 1.15rem);
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 24px;
      padding-bottom: 72px;
    }

    .card {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 28px 24px;
      display: flex;
      flex-direction: column;
      gap: 12px;
      transition: transform 0.2s ease, border-color 0.2s ease;
    }

    .card:hover {
      transform: translateY(-4px);
      border-color: var(--accent);
    }

    .icon {
      font-size: 2.25rem;
      line-height: 1;
    }

    .card h2 {
      font-size: 1.25rem;
      font-weight: 700;
    }

    .card p {
      color: var(--muted);
      font-size: 0.95rem;
      flex-grow: 1;
    }

    .btn {
      display: inline-block;
      text-align: center;
      text-decoration: none;
      background: var(--accent);
      color: #0b0d12;
      font-weight: 600;
      padding: 12px 20px;
      border-radius: 10px;
      margin-top: 8px;
      transition: background 0.2s ease;
    }

    .btn:hover { background: var(--accent-hover); }

    footer {
      text-align: center;
      color: var(--muted);
      font-size: 0.85rem;
      padding: 24px 0 40px;
      border-top: 1px solid var(--border);
    }
  </style>
</head>
<body>

  <header class="container">
    <h1>Erick</h1>
    <p>Apresento protótipos visuais modernos para empresas.</p>
  </header>

  <main class="container">
    <section class="grid">

      <article class="card">
        <div class="icon">💈</div>
        <h2>Barbearia</h2>
        <p>Site elegante com serviços, preços e agendamento online.</p>
        <a class="btn" href="https://exemplo.com" target="_blank" rel="noopener">Ver Demonstração</a>
      </article>

      <article class="card">
        <div class="icon">🍔</div>
        <h2>Hamburgueria</h2>
        <p>Cardápio atrativo e pedidos rápidos para conquistar clientes.</p>
        <a class="btn" href="https://exemplo.com" target="_blank" rel="noopener">Ver Demonstração</a>
      </article>

      <article class="card">
        <div class="icon">🦷</div>
        <h2>Consultório Odontológico</h2>
        <p>Visual limpo e confiável, com tratamentos e contato direto.</p>
        <a class="btn" href="https://exemplo.com" target="_blank" rel="noopener">Ver Demonstração</a>
      </article>

    </section>
  </main>

  <footer>
    © 2026 Erick. Todos os direitos reservados.
  </footer>

</body>
</html>