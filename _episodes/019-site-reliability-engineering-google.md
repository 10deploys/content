---
title: Site Reliability Engineering no Google
date: 2018-03-11 13:00:00

image:
  position: top right
  description: |
    Prédio com logo do Google, por Mike Blake, todos os direitos reservados.

number: "019"

recording:
  recorded: yes
  date: 2018-03-15 22:00:00 -0300
  summary: |
    SRE é uma disciplina que incorpora aspectos de engenharia de software à operação de TI. Para uns, é uma
    implementação específica de DevOps. Yves Junqueira explica como SRE muda a operação de TI, compartilhando o que
    viu em seus 10 anos no Google.
  audio_file: https://d3ctxlq1ktw2nl.cloudfront.net/production/2018-7-26/4256264-44100-2-060e908a948ab.m4a
  soundcloud_id: 416286582
  youtube_id: NLrFyYuKuWI

toc:
  - title: Abertura
    instant: "0:00"
  - title: Apresentação do tema
    instant: "0:24"
  - title: Promoção 4Linux do curso DevSecOps com o Bruno Dantas
    instant: "1:09"
  - title: Quem é Yves Junqueira?
    instant: "1:51"
  - title: "O projeto open-source YourBase"
    instant: "3:25"
  - title: "Como mudou de Relações Internacionais para trabalhar com computação?"
    instant: "4:21"
  - title: Você já era SRE em 2008?
    instant: "6:51"
  - title: O que é um SRE?
    instant: "8:55"
  - title: Evolução do SRE e influências da indústria
    instant: "11:09"
  - title: "Otimização prematura vs requisitos de performance: como o Google faz?"
    instant: "14:35"
  - title: O que é importante monitorar quando se tem essa mentalidade de performance?
    instant: "18:31"
  - title: Como é o stack da infraestrutura do Google?
    instant: "23:03"
  - title: Inovações do Google que viraram produtos open-source
    instant: "29:32"
  - title: Como o Google lida e aprende com as falhas?
    instant: "31:33"
  - title: Como os times são estruturados?
    instant: "37:01"
  - title: Como criar produtos com suporte a modo degradado?
    instant: "40:04"
  - title: |
      Pergunta do ouvinte (Bruno Dantas): Com quais produtos o Yves trabalhou no Google? Como foi a transição para
      tech lead?
    instant: "44:03"
  - title: Dicas para quem está virando um tech lead, coordenador ou gerente
    instant: "49:40"
  - title: |
      Pergunta da ouvinte (Daniela Vieira): Como funcionam os processos de testes automatizados nos times que o
      Yves trabalhou?
    instant: "52:41"
  - title: Dicas para quem está começando e quer ser um SRE
    instant: "59:30"
  - title: Qual livro abriu a mente em relação à programação?
    instant: "1:02:41"
  - title: Qual mentalidade é importantante para empreendedores inovarem como o Google?
    instant: "1:03:42"
  - title: O que o Google faz certo para reter um funcionário por 10 anos?
    instant: "1:06:13"
  - title: Recomendações
    instant: "1:08:40"

guests:
  - name: Yves Junqueira
    biography: |
      Yves Junqueira foi SRE no Google por quase 10 anos. Antes disso, trabalhou em empresas de hosting, no governo
      federal em Brasília e na fábrica de biscoitos Mabel. Atualmente mora em Seattle nos EUA e ajuda a acelerar a
      infra de times de desenvolvimento.
    social_media:
      Facebook: https://facebook.com/yvesjunqueira
      Twitter: https://twitter.com/cetico
      GitHub: https://github.com/nictuku
      LinkedIn: https://linkedin.com/in/yvesjunqueira

references:
  - title: The Production Environment at Google, from the Viewpoint of an SRE
    author: JC van Winkel
    year: 2017
    type: book
    url: https://landing.google.com/sre/book/chapters/production-environment.html
  - title: The Google File System
    author: Sanjay Ghemawat, Howard Gobioff e Shun-Tak Leung
    year: 2003
    type: doc
    url: https://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf
  - title: "Site Reliability Engineering: How Google Runs Production Systems"
    author: Betsy Beyer, Chris Jones, Jennifer Petoff e Niall Murphy
    year: 2016
    type: book
    url: http://amzn.to/2HNtuvv
  - title: Programming Pearls
    author: Jon Bentley
    year: 1999
    type: book
    url: http://amzn.to/2FQ6j7a
  - title: "Code Complete: A Practical Handbook of Software Construction"
    author: Steve McConnell
    year: 2004
    type: book
    url: http://amzn.to/2FMCLXT
  - title: The Go Programming Language
    author: ~
    year: ~
    type: library
    url: https://golang.org
  - title: Kubernetes
    author: ~
    year: ~
    type: tool
    url: https://kubernetes.io
  - title: YourBase
    author: ~
    year: ~
    type: tool
    url: https://yourbase.io

recommendations:
  - title: "The Hard Thing About Hard Things: Building a Business When There Are No Easy Answers"
    author: Ben Horowitz
    year: 2014
    type: book
    url: http://amzn.to/2DCUsU1
    who: Yves Junqueira
  - title: "Production-Ready Microservices: Building Standardized Systems Across an Engineering Organization"
    author: Susan J. Fowler
    year: 2016
    type: book
    url: http://amzn.to/2GbT9R4
    who: Yves Junqueira
  - title: "Consciousness and the Brain: Deciphering How the Brain Codes Our Thoughts"
    author: Stanislas Dehaene
    year: 2014
    type: book
    url: http://amzn.to/2IB1DzO
    who: Yves Junqueira
  - title: Dirty Money
    author: Alex Gibney
    year: 2018
    type: movie
    url: https://www.netflix.com/title/80118100
    who: Fernando Ike
  - title: "Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation"
    author: Jez Humble e David Farley
    year: 2010
    type: book
    url: http://amzn.to/2GJ7hOB
    who: Fernando Ike
  - title: "Clean Architecture: A Craftsman's Guide to Software Structure and Design"
    author: Robert C. Martin (Uncle Bob)
    year: 2017
    type: book
    url: http://amzn.to/2FSZ8XL
    who: Eriksen Costa
  - title: Show Liam Gallagher, Audio Club, São Paulo - SP (21/03/2018 - cancelado)
    author: ~
    year: ~
    type: music
    url: http://www.tenhomaisdiscosqueamigos.com/2018/01/24/liam-gallagher-ingressos
    who: Eriksen Costa

media_credits:
  - description: ~
    name: Prédio com logo do Google
    type: picture
    page: "https://www.reuters.com/article/us-google-cyber/google-launches-advanced-gmail-security-features-for-high-risk-users-idUSKBN1CM1GP"
    author: Mike Blake
    author_page: "https://widerimage.reuters.com/photographer/mike-blake"
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

Site Reliability Engineering (SRE) é uma disciplina nascida no Google que incorpora aspectos de engenharia de software à
operação de TI. Benjamin Treynor Sloss, VP de Engenharia do Google e criador do termo diz que confiabilidade
(_reliability_) é a característica mais fundamental de um produto: um sistema não é muito útil se ninguém consegue
usá-lo.

SRE é uma disciplina ampla que nasceu em um momento de rápida evolução dos _web services_ onde suas práticas devem, em
parte, às peculiaridades da infraestrutura do Google. Para uns, é uma implementação específica de DevOps. Yves Junqueira
trabalhou por 10 anos como Site Reliability Engineer no Google e compartilha sua experiência.
