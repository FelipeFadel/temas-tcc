<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>temas-tcc — Sumário</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0f1724; --card:#0b1220; --muted:#94a3b8; --accent:#7c3aed; --glass: rgba(255,255,255,0.03);
      --maxw:980px;
    }
    *{box-sizing:border-box}
    body{font-family:Inter,system-ui,Segoe UI,Roboto,Helvetica,Arial,sans-serif;margin:0;background:linear-gradient(180deg,#071029 0%, #071a2b 60%);color:#e6eef8;display:flex;align-items:flex-start;justify-content:center;padding:48px 20px}
    .container{width:100%;max-width:var(--maxw)}
    header{display:flex;gap:16px;align-items:center;margin-bottom:18px}
    .logo{width:64px;height:64px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#3b82f6);display:flex;align-items:center;justify-content:center;font-weight:700;color:white;box-shadow:0 6px 18px rgba(124,58,237,0.18)}
    h1{font-size:20px;margin:0}
    p.lead{margin:4px 0 0;color:var(--muted)}

    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border-radius:14px;padding:20px;margin-bottom:16px;box-shadow:0 6px 20px rgba(2,6,23,0.6);border:1px solid rgba(255,255,255,0.03)}
    h2{margin:0 0 6px;font-size:16px}
    h3{margin:12px 0 8px;font-size:14px}
    ul{margin:8px 0 12px 20px}
    li{margin:6px 0}
    code{background:rgba(255,255,255,0.03);padding:2px 6px;border-radius:6px;color:#d1d5db}
    .muted{color:var(--muted);font-size:13px}
    .grid{display:grid;grid-template-columns:1fr;gap:12px}
    .pill{display:inline-block;padding:6px 10px;border-radius:999px;background:var(--glass);font-weight:600;color:var(--muted);font-size:13px;margin-right:8px}

    .meta{display:flex;gap:8px;flex-wrap:wrap;margin-top:8px}

    /* nice code block */
    pre {background:rgba(10,14,20,0.6);padding:12px;border-radius:10px;overflow:auto;border:1px solid rgba(255,255,255,0.02);color:#cbd5e1}

    footer{margin-top:14px;color:var(--muted);font-size:13px}

    @media(min-width:900px){.grid{grid-template-columns:1fr 1fr}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="logo">TCC</div>
      <div>
        <h1># temas-tcc</h1>
        <p class="lead">Esse repositório está em construção e depois será renovado com o tema definitivo do TCC. Por enquanto ele organiza os possíveis temas para explorar no README. Espero que algum dos temas seja bom hahaah</p>
      </div>
    </header>

    <section class="card">
      <h2>Execução de Jogos no Navegador e na Nuvem: Análise, Comparação e Protótipo Open Source de Cloud Gaming</h2>
      <p class="muted">Investigar como jogos funcionam no navegador usando <code>WebGL/WebAssembly</code> e comparar com jogos executados totalmente na nuvem através de cloud gaming (como<code> Xbox Cloud Gaming</code> e <code>GeForce Now</code>).<br>
      Além da análise, o tema propõe desenvolver um protótipo <code>open source</code> que permita a qualquer pessoa montar seu próprio sistema simples de jogos via streaming.</p>

      <h3>O que seria feito na prática</h3>
      <ol>
        <li><strong>Estudo técnico:</strong>
          <ul>
            <li>Como <code>WebGL</code> usa GPU/CPU local;</li>
            <li>Papel do <code>WebAssembly</code> na performance do navegador;</li>
            <li>Protocolos usados por jogos: <code>HTTP</code> (assets), <code>WebSocket</code> (tempo real), <code>WebRTC/UDP</code> (streaming);</li>
            <li>Como funciona um serviço completo de cloud gaming (encode, transporte, decode).</li>
          </ul>
        </li>
        <li><strong>Comparação entre dois modelos:</strong>
          <ul>
            <li>Execução local (<code>WebGL/WASM</code>);</li>
            <li>Execução na nuvem (<code>Cloud Gaming</code>).</li>
            <p class="muted">Comparando:</p>
            <ul>
              <li>Latência;</li>
              <li>Consumo de banda;</li>
              <li>Uso de hardware;</li>
              <li>Custos e escalabilidade de infraestrutura;</li>
            </ul>
          </ul>
        </li>
        <li><strong>Implementar um pequeno sistema que:</strong>
          <ul>
            <li>Roda um jogo no servidor</li>
            <li>Captura e codifica o vídeo</li>
            <li>Envia via WebRTC</li>
            <li>Recebe inputs do cliente</li>
            <li>Código aberto e documentação para permitir que qualquer pessoa crie sua própria versão de cloud gaming.</li>
          </ul>
        </li>
      </ol>

      <h3>O que já existe de parecido</h3>
      <ul>
        <li>Xbox Cloud Gaming</li>
        <li>NVIDIA GeForce Now</li>
        <li>Google Stadia (descontinuado)</li>
        <li>Frameworks como Unity WebGL, Godot WebAssembly</li>
      </ul>

      <h3>Diferencias do tema</h3>
      <ul>
        <li>Foco educacional e open source: qualquer pessoa poderá instalar, modificar e entender um sistema de cloud gaming.</li>
        <li>Comparação técnica entre execução local e remota.</li>
        <li>Protótipo funcional que demonstra:
          <ul>
            <li>streaming em baixa latência</li>
            <li>input remoto</li>
            <li>impacto da rede</li>
          </ul>
        </li>
      </ul>
    </section>

    <section class="card">
      <h2>Jogo de Puzzles com Imagens Geradas Dinamicamente por Inteligência Artificial (idealizado pelo professor Andreas Jessé)</h2>
      <p class="muted">Criar um jogo ou aplicativo de puzzles em que todas as imagens usadas nos desafios são geradas por IA, de forma dinâmica e potencialmente em tempo real, garantindo que cada jogador receba enigmas únicos e nunca repetidos.</p>

      <h3>O que seria feito na prática:</h3>
      <p class="muted">(pensar)</p>

      <h3>O que ja existe de parecido:</h3>
      <p class="muted">(pensar)</p>

      <h3>Diferenciais da proposta:</h3>
      <ul>
        <li>Conteúdo dinamico;</li>
        <li>Alta automatização.</li>
        <li>Tema atual e altamente tecnológico, combinando IA, engines de jogos e design procedural.</li>
        <li>Possibilidade de extensão com:
          <ul>
            <li>escolha de estilo pelo jogador,</li>
            <li>puzzles temáticos,</li>
            <li>variação de dificuldade gerada por IA.</li>
          </ul>
        </li>
      </ul>
    </section>

    <section class="card">
      <h2>Sistema de Versionamento e CI/CD Especializado para Desenvolvimento de Jogos</h2>
      <p class="muted">Criar uma plataforma de versionamento e <code>CI/CD</code> voltada especificamente para desenvolvimento de jogos, oferecendo algo que Git/GitHub não atendem bem: entendimento real de cenas, GameObjects e componentes usados em engines como Unity e Godot.</p>

      <h3>O que seria feito na prática:</h3>
      <ul>
        <li>Desenvolver um sistema de versionamento capaz de interpretar arquivos de cena/prefab e mostrar diferenças de forma visual (objetos, componentes, valores alterados);</li>
        <li>Criar uma dashboard web onde a equipe possa ver o estado do projeto, mudanças, conflitos e responsáveis por cada parte;</li>
        <li>Implementar uma pipeline CI/CD para jogos, automatizando;</li>
        <li>Build em WebGL/PC;</li>
        <li>Compressão;</li>
        <li>Upload automático para itch.io;</li>
        <li>Execução de testes básicos do jogo;</li>
        <li>Criar plugin simples para as engines exibindo o status do versionamento dentro da própria engine.</li>
      </ul>

      <h3>O que ja existe de parecido</h3>
      <ul>
        <li>Unity Version Control (PlasticSCM)</li>
        <li>Perforce Helix</li>
        <li>Git LFS</li>
        <li>Pipelines genéricas como GitHub Actions / GitLab CI</li>
      </ul>

      <h3>Diferenciais da minha proposta</h3>
      <ul>
        <li>Versionamento realmente interpretado para jogos (GameObjects, componentes, cenas).</li>
        <li>Visualização clara das mudanças, evitando merges destrutivos.</li>
        <li>CI/CD totalmente voltado para jogos, com build automatizado e envio para itch.io.</li>
        <li>Solução mais simples e acessível, pensada para equipes indie, estudantes e game jams.</li>
      </ul>
    </section>

    <footer class="card muted">
      Essa página é uma versão visual do README — o conteúdo textual foi mantido exatamente como no original.
    </footer>
  </div>
</body>
</html>
