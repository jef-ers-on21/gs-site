# gs-site

<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>Gaming Simulators GS</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
:root{
  --bg:#020f0a;
  --card:#0b2e22;
  --accent:#ffdf00;
  --text:#ffffff;
  --muted:#9aa;
}

*{box-sizing:border-box}

body{
  margin:0;
  font-family:Inter,Segoe UI,Arial,sans-serif;
  background:linear-gradient(180deg,#02140e,#000);
  color:var(--text);
  line-height:1.6;
}

header{
  padding:28px 20px;
  text-align:center;
  background:rgba(0,0,0,.7);
  border-bottom:1px solid rgba(255,255,255,.08);
}

header h1{
  margin:0;
  color:var(--accent);
  font-size:32px;
}

header p{
  margin:6px 0 0;
  color:var(--muted);
}

section{
  padding:40px 20px;
  max-width:1100px;
  margin:auto;
}

.card{
  background:var(--card);
  border-radius:20px;
  padding:28px;
  margin-bottom:28px;
}

h2{
  color:var(--accent);
  margin-top:0;
}

.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
  gap:22px;
}

button{
  padding:16px;
  border:none;
  border-radius:16px;
  font-weight:700;
  cursor:pointer;
  background:var(--accent);
  color:#000;
  font-size:16px;
}

button.alt{
  background:transparent;
  color:var(--accent);
  border:2px solid var(--accent);
}

footer{
  text-align:center;
  padding:30px 20px;
  font-size:14px;
  color:var(--muted);
  background:rgba(0,0,0,.5);
}

.badge{
  display:inline-block;
  padding:6px 12px;
  border-radius:12px;
  background:rgba(255,223,0,.15);
  color:var(--accent);
  font-size:13px;
  margin-bottom:10px;
}
</style>
</head>

<body>

<header>
  <h1>🎮 Gaming Simulators GS</h1>
  <p>Simuladores onde decisões importam</p>
</header>

<section>
  <div class="card">
    <span class="badge">Manifesto</span>
    <h2>Quem somos</h2>
    <p>
      A Gaming Simulators GS é um estúdio brasileiro focado em criar
      simuladores que vão além do entretenimento.
      Aqui, cada escolha gera consequência.
    </p>
    <p>
      Não seguimos fórmulas prontas. Criamos experiências que grandes
      empresas não arriscam.
    </p>
  </div>

  <div class="card">
    <span class="badge">Fundamentos</span>
    <h2>Objetivos Fundamentais</h2>
    <div class="grid">
      <div>
        <h3>🎯 Autenticidade</h3>
        <p>Jogos conectados à realidade social, cultural e humana.</p>
      </div>
      <div>
        <h3>⚖️ Consequência</h3>
        <p>Decisões importam. Não existe caminho perfeito.</p>
      </div>
      <div>
        <h3>🧠 Profundidade</h3>
        <p>Sistemas simples, mas com impacto real.</p>
      </div>
      <div>
        <h3>🚀 Inovação</h3>
        <p>Explorar ideias que o mercado tradicional evita.</p>
      </div>
    </div>
  </div>

  <div class="card">
    <span class="badge">Produtos</span>
    <h2>Experiências GS</h2>
    <div class="grid">
      <div>
        <h3>⚽ GS Futebol Raiz</h3>
        <p>Simulador social de futebol brasileiro.</p>
        <small>Alpha v0.1 disponível</small>
      </div>
      <div>
        <h3>📖 GS Bible</h3>
        <p>Jogo educativo baseado em conhecimento bíblico.</p>
        <small>Em desenvolvimento</small>
      </div>
      <div>
        <h3>📜 GS História</h3>
        <p>Decisões históricas e suas consequências.</p>
        <small>Planejado</small>
      </div>
      <div>
        <h3>🏛️ GS Política</h3>
        <p>Simulação de poder, sociedade e opinião pública.</p>
        <small>Planejado</small>
      </div>
    </div>
  </div>

  <div class="card">
    <span class="badge">Visão</span>
    <h2>O futuro da GS</h2>
    <p>
      Nosso objetivo é construir um ecossistema de simuladores
      conectados, onde cada jogo representa uma dimensão da realidade.
    </p>
    <p>
      A GS nasce pequena, mas com visão de estúdio global.
    </p>
  </div>

  <div class="card">
    <h2>Contato & Comunidade</h2>
    <p>
      Quer acompanhar o desenvolvimento ou apoiar a GS?
    </p>
    <button onclick="alert('Contato em breve')">Entrar em contato</button>
  </div>
</section>

<footer>
© 2025 – Gaming Simulators GS<br>
Estúdio independente brasileiro
</footer>

</body>
</html>
