# temas-tcc
Esse repositório está em construção e depois será renovado com o tema definitivo do TCC. Por enquanto ele organiza os possíveis temas para explorar no README. Espero que algum dos temas seja bom hahaah

## Sistema de Versionamento e CI/CD Especializado para Desenvolvimento de Jogos
  Criar uma plataforma de versionamento e CI/CD voltada especificamente para desenvolvimento de jogos, oferecendo algo que Git/GitHub não atendem bem: entendimento real de cenas, GameObjects e componentes usados em engines como Unity e Godot.
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
