---
title: Tratando erros corretamente
date: 2018-04-01 19:30:00

image:
  position: bottom right
  description: |
    Bombeiro em frente a uma casa em chamas, por Jeff Chiu (para a AP), todos os direitos reservados.

number: "020"

recording:
  recorded: yes
  date: 2018-04-12 22:00:00 -0300
  summary: |
    Os cenários de erros compõe uma parte importante no ciclo de vida das aplicações. No entanto, muitos desenvolvedores
    não tratam os erros com a devida atenção. Lais Varejão (Vinta Software) e Augusto Pascutti (Easy) explicam como
    tratar os erros corretamente.
  audio_file: https://d3ctxlq1ktw2nl.cloudfront.net/production/2018-7-26/4256297-44100-2-831b2767dbce1.m4a
  soundcloud_id: 429109635
  youtube_id: 9r5H-_aS49c

toc:
  - title: Abertura
    instant: "0:00"
  - title: Ganhador do concurso 4Linux (curso DevSecOps) e código de desconto para o DevOpsDays SP
    instant: "1:30"
  - title: Apresentação do tema
    instant: "2:53"
  - title: Quem é Lais Varejão?
    instant: "3:38"
  - title: Quem é Augusto Pascutti?
    instant: "4:52"
  - title: Como é a participação da mulher em TI?
    instant: "6:38"
  - title: Pra que servem os logs?
    instant: "9:46"
  - title: Logs são como uma máquina do tempo
    instant: "13:56"
  - title: Monitoramento em tempo real usando logs
    instant: "14:31"
  - title: Definir a severidade dos logs é importante para servir as necessidades dos diferentes usuários
    instant: "17:55"
  - title: Mensagens de log e recuperação de incidentes
    instant: "20:20"
  - title: O que é a heurística da disponibilidade?
    instant: "22:05"
  - title: A importância dos processos de recuperação de incidentes e o caso GitLab
    instant: "26:31"
  - title: Aprendendo com as falhas e a segurança psicológica
    instant: "29:45"
  - title: Psicologia e frequência dos alertas
    instant: "35:54"
  - title: Ferramentas de monitoramento como serviço
    instant: "43:59"
  - title: Estratégias para definir os limites para o envio de alertas e alinhamento com as pessoas de negócio
    instant: "45:34"
  - title: "Comentário do ouvinte Yago Nobre: só alertar se alguém precisar fazer alguma coisa"
    instant: "49:03"
  - title: Dicas práticas para escrever boas mensagens de erro
    instant: "49:39"
  - title: Usar a revisão de código para verificar se os logs fazem sentido
    instant: "54:01"
  - title: O Domain-Driven Design é uma prática relevante para escrever boas mensagens de log
    instant: "54:30"
  - title: Como começar a escrever logs?
    instant: "57:40"
  - title: Conclusões
    instant: "1:02:03"
  - title: Recomendações
    instant: "1:03:38"

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

references:
  - title: "Errors: How they live, eat and reproduce"
    author: Augusto Pascutti
    year: 2018
    type: presentation
    url: https://pt.slideshare.net/augustopascutti/errors-89819861
  - title: "Superando Crises: Um guia para desenvolvedores"
    author: Lais Varejão
    year: 2018
    type: presentation
    url: https://docs.google.com/presentation/d/1D5MbTwAV8yiVzvBcF1TiiI6N_qs4nEMMPp8cldkmzHo/edit#slide=id.p
  - title: The psycologhy of alert design
    author: Lindsay Holmwood
    year: 2013
    type: movie
    url: https://vimeo.com/75321812
  - title: Domain-Driven Design Distilled
    author: Vaughn Vernon
    year: 2016
    type: book
    url: https://amzn.to/2HE0qYq

recommendations:
  - title: The Evolution of Cooperation
    author: Robert Axelrod
    year: 2006
    type: book
    url: https://amzn.to/2JQVOi5
    who: Augusto Pascutti
  - title: Modern Agile
    author: Joshua Kerievsky
    year: 2016
    type: youtube
    url: https://www.youtube.com/watch?v=RKS4zs6gPw4
    who: Lais Varejão
  - title: The Punisher
    author: Andy Goddard
    year: 2017
    type: movie
    url: https://www.netflix.com/title/80117498
    who: Fernando Ike
  - title: Platform Revolution
    author: Geoffrey G. Parker, Marshall W. Van Alstyne e Sangeet Paul Choudary
    year: 2017
    type: book
    url: https://amzn.to/2J2qBYl
    who: Fernando Ike
  - title: "Tirando de Letra: Orientações Simples e Práticas Para Escrever Bem"
    author: Chico Moura e Wilma Moura
    year: 2017
    type: book
    url: https://amzn.to/2J3l1F5

media_credits:
  - description: ~
    name: Bombeiro em frente a uma casa em chamas
    type: picture
    page: "http://www.kpbs.org/news/2017/oct/10/public-calamity-as-california-wildfires-leave"
    author: Jeff Chiu (para a AP)
    author_page: "https://www.linkedin.com/in/jeff-chiu-08668864"
    license: copyright
  - name: Dupree Blues
    description: ~
    type: music
    page: "https://commons.wikimedia.org/wiki/File:Blind_Willie_Walker_-_Dupree_Blues.ogg"
    author: Blind Willie Walker
    author_page: "https://en.wikipedia.org/wiki/Blind_Willie_Walker"
    license: CC0
  - name: Jazz Me Blues
    description: ~
    type: music
    page: "https://commons.wikimedia.org/wiki/File:OriginalDixielandJassBand-JazzMeBlues.ogg"
    author: Original Dixieland Jazz Band
    author_page: "https://en.wikipedia.org/wiki/Original_Dixieland_Jass_Band"
    license: CC0
---

Os cenários de erros compõe uma parte importante no ciclo de vida das aplicações. No entanto, vários vieses cognitivos
fazem com que desenvolvedores não tratem os erros com a devida atenção.

Um exemplo de viés é o da heurística da disponibilidade, que é a tendência de prever que algo funcionará ou será válido
pelo julgamento de exemplos mais recentes em detrimento de uma avaliação que contemple experiências mais antigas.

Lais Varejão (Vinta Software) e Augusto Pascutti (Easy) explicam como tratar os erros corretamente: como criar boas
mensagens de erro, como enriquecer o contexto do erro, quais os tipos de exceções que você pode aplicar em seu projeto
e como tudo isso é importante para processos como recuperação de desastre e *post-mortem*.

### Ganhador do concurso 4Linux

O José Geraldo foi o ganhador do concurso 4Linux e vai fazer, gratuitamente, o curso
[DevSecOps](https://www.4linux.com.br/curso/devsecops).

### Código de desconto do DevOpsDays São Paulo

O código de desconto para o [DevOpsDays SP](https://www.devopsdays.org/events/2018-sao-paulo/welcome/) é
`DOD10DEPLOYS10`. O desconto é de 10% do valor da inscrição.
