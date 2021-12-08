 - 👋 Hi, I’m @Rennylsonlemos19.
-🤗Seja todos muito Bem-Vindos ao meu Github.
-🖖Tenho 19 anos.
-🎶Gosto bastande de músicas.
-🖥️📘Atualmente estou estudando Desenvolvimento de sistemas (DS).
-🙏🗝️👨‍Aqui eu vou esta postando os meus projetos (iniciante) e juntos veremos minha evolução.💻
nome : Gerar Dados

em :
  cronograma : # executar a cada 12 horas
    - cron : " * * / 12 * * * "
  workflow_dispatch :

empregos :
  construir :
    nome : Trabalhos para atualizar dados
    roda em : ubuntu-mais recente
    passos :
      # Animação de cobra
      - usa : Platane / snk @ master
        id : snake-gif
        com :
          github_user_name : rafaballerini
          svg_out_path : dist / github-customization-grid-snake.svg

      - usa : crazy-max/ghaction-github-pages@v2.1.3
        com :
          target_branch : output
          build_dir : dist
        env :
          GITHUB_TOKEN : $ {{secrets.GITHUB_TOKEN}}
