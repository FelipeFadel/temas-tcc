# temas-tcc

Esse repositório está em construção e depois será renovado com o tema definitivo do TCC. Por enquanto ele organiza os possíveis temas para explorar no README. Espero que algum dos temas seja bom hahaah

## Execução de Jogos no Navegador e na Nuvem: Análise, Comparação e Protótipo Open Source de Cloud Gaming

  Investigar como jogos funcionam no navegador usando `WebGL/WebAssembly` e comparar com jogos executados totalmente na nuvem através de cloud gaming (como` Xbox Cloud Gaming` e `GeForce Now`).
  Além da análise, o tema propõe desenvolver um protótipo `open source` que permita a qualquer pessoa montar seu próprio sistema simples de jogos via streaming.
  
### O que seria feito na prática

1. Estudo técnico:
  - Como `WebGL` usa GPU/CPU local;
  - Papel do `WebAssembly` na performance do navegador;
  - Protocolos usados por jogos: `HTTP` (assets), `WebSocket` (tempo real), `WebRTC/UDP` (streaming);
  - Como funciona um serviço completo de cloud gaming (encode, transporte, decode).
2. Comparação entre dois modelos:
  - Execução local (`WebGL/WASM`);
  - Execução na nuvem (`Cloud Gaming`).
  Comparando:
  - Latência;
  - Consumo de banda;
  - Uso de hardware;
  - Custos e escalabilidade de infraestrutura;
3. Implementar um pequeno sistema que:
  - Roda um jogo no servidor
  - Captura e codifica o vídeo
  - Envia via WebRTC
  - Recebe inputs do cliente
  - Código aberto e documentação para permitir que qualquer pessoa crie sua própria versão de cloud gaming.

### O que já existe de parecido
  - Xbox Cloud Gaming
  - NVIDIA GeForce Now
  - Google Stadia (descontinuado)
  - Frameworks como Unity WebGL, Godot WebAssembly
  
### Diferencias do tema
  - Foco educacional e open source: qualquer pessoa poderá instalar, modificar e entender um sistema de cloud gaming.
  - Comparação técnica entre execução local e remota.
  - Protótipo funcional que demonstra:
  - streaming em baixa latência
  - input remoto
  - impacto da rede

## Jogo de Puzzles com Imagens Geradas Dinamicamente por Inteligência Artificial (idealizado pelo professor Andreas Jessé)
  Criar um jogo ou aplicativo de puzzles em que todas as imagens usadas nos desafios são geradas por IA, de forma dinâmica e potencialmente em tempo real, garantindo que cada jogador receba enigmas únicos e nunca repetidos.
### O que seria feito na prática:
(pensar)
### O que ja existe de parecido:
(pensar)
### Diferenciais da proposta:
  - Conteúdo dinamico;
  - Alta automatização.
  - Tema atual e altamente tecnológico, combinando IA, engines de jogos e design procedural.
  Possibilidade de extensão com:
  - escolha de estilo pelo jogador,
  - puzzles temáticos,
  - variação de dificuldade gerada por IA.

## Sistema de Versionamento e CI/CD Especializado para Desenvolvimento de Jogos
  Criar uma plataforma de versionamento e `CI/CD` voltada especificamente para desenvolvimento de jogos, oferecendo algo que Git/GitHub não atendem bem: entendimento real de cenas, GameObjects e componentes usados em engines como Unity e Godot.
### O que seria feito na prática:
  - Desenvolver um sistema de versionamento capaz de interpretar arquivos de cena/prefab e mostrar diferenças de forma visual (objetos, componentes, valores alterados);
  - Criar uma dashboard web onde a equipe possa ver o estado do projeto, mudanças, conflitos e responsáveis por cada parte;
  - Implementar uma pipeline CI/CD para jogos, automatizando;
  - Build em WebGL/PC;
  - Compressão;
  - Upload automático para itch.io;
  - Execução de testes básicos do jogo;
  - Criar plugin simples para as engines exibindo o status do versionamento dentro da própria engine.
### O que ja existe de parecido
  - Unity Version Control (PlasticSCM)
  - Perforce Helix
  - Git LFS
  - Pipelines genéricas como GitHub Actions / GitLab CI
### Diferenciais da minha proposta
  - Versionamento realmente interpretado para jogos (GameObjects, componentes, cenas).
  - Visualização clara das mudanças, evitando merges destrutivos.
  - CI/CD totalmente voltado para jogos, com build automatizado e envio para itch.io.
  - Solução mais simples e acessível, pensada para equipes indie, estudantes e game jams.
