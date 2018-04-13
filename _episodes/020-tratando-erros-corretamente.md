---
title: Tratando erros corretamente
date: 2018-04-01 19:30:00

image:
  position: bottom right
  description: |
    Bombeiro em frente a uma casa em chamas, por Jeff Chiu (para a AP), todos os direitos reservados.

number: "020"

recording:
  recorded: no
  date: 2018-04-12 22:00:00 -0300
  summary: |
    Os cenários de erros compõe uma parte importante no ciclo de vida das aplicações. No entanto, muitos desenvolvedores
    não tratam os erros com a devida atenção. Lais Varejão (Vinta Software) e Augusto Pascutti (Easy) explicam como
    tratar os erros corretamente.
  soundcloud_id: ~
  youtube_id: 9r5H-_aS49c

toc: ~

guests:
  - name: Lais Varejão
    biography: |
      Lais Varejão é desenvolvedora full-stack e gerente de projetos na Vinta Software. Organizadora do Django Girls
      Recife, vislumbra um futuro com mais mulheres na computação. Engenheira de Software por formação, tem 6 anos de
      experiência no mercado. Atualmente lidera uma equipe de desenvolvimento onde aplica metodologias ágeis.
    social_media:
      Twitter: https://twitter.com/laisvarejao
      GitHub: https://github.com/laisvarejao
      LinkedIn: https://www.linkedin.com/in/lais-varej%C3%A3o-0a441224
  - name: Augusto Pascutti
    biography: |
      Augusto Pascutti é Head de Arquitetura na Easy. Desenvolvedor web há mais de 10 anos, é apaixonado sobre pessoas
      (comunidades, práticas ágeis), código (open source, refactoring, Integração Contínua) e linguagens (PHP,
      JavaScript, Go, Java e padrões web).
    social_media:
      Facebook: http://facebook.com/augusto.pascutti
      Twitter: https://twitter.com/augustohp
      GitHub: https://github.com/augustohp
      LinkedIn: https://www.linkedin.com/in/augustohp

references: ~

recommendations: ~

media_credits:
  - description: ~
    name: Bombeiro em frente a uma casa em chamas
    type: picture
    page: "http://www.kpbs.org/news/2017/oct/10/public-calamity-as-california-wildfires-leave"
    author: Jeff Chiu (para a AP)
    author_page: "https://www.linkedin.com/in/jeff-chiu-08668864"
    license: copyright
---

Os cenários de erros compõe uma parte importante no ciclo de vida das aplicações. No entanto, vários vieses cognitivos
fazem com que desenvolvedores não tratem os erros com a devida atenção.

Um exemplo de viés é o da heurística da disponibilidade, que é a tendência de prever que algo funcionará ou será válido
pelo julgamento de exemplos mais recentes em detrimento de uma avaliação que contemple experiências mais antigas.

Lais Varejão (Vinta Software) e Augusto Pascutti (Easy) explicam como tratar os erros corretamente: como criar boas
mensagens de erro, como enriquecer o contexto do erro, quais os tipos de exceções que você pode aplicar em seu projeto
e como tudo isso é importante para processos como recuperação de desastre e *post-mortem*.
