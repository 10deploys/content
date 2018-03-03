---
title: Infraestrutura imutável
date: 2018-01-18 21:00:00

image:
  position: top center
  description: |
    Sítio arqueológico de Stonehenge, por Walkers in The Way, sob domínio público.

number: "017"

recording:
  recorded: yes
  date: 2018-01-18 21:00:00
  summary: |
    Infraestrutura imutável é uma forma de conceber a infraestrutura que provê estabilidade, eficiência e fidelidade
    usando o conceito de imutabilidade. Fernando Ike explica as vantagens e as características dessa forma de gerir
    a infraestrutura.
  soundcloud_id: 385763444
  youtube_id: x527pxPQJDk

toc:
  - title: Abertura
    instant: "0:00"
  - title: Mudança de nome do podcast
    instant: "0:59"
  - title: Apresentação do tema
    instant: "2:53"
  - title: A história da infraestrutura imutável
    instant: "3:23"
  - title: Problemas comuns com a gestão manual de código
    instant: "8:02"
  - title: O que é infrastrutura imutável e quais seus benefícios
    instant: "11:36"
  - title: Eliminação de imprevisibilidade
    instant: "16:56"
  - title: Automação de configuração sozinha não traz os benefícios da infraestrutura imutável
    instant: "19:18"
  - title: Como começar?
    instant: "21:22"
  - title: "Os vários nomes da infraestrutura imutável: immutable deployments, phoenix server, pets vs cattle"
    instant: "24:21"
  - title: Posso aplicar patches emergenciais nas instâncias ou devo criar uma nova imagem sempre?
    instant: "27:30"
  - title: Qual o primeiro passo?
    instant: "36:02"
  - title: Facilita a resolução de problemas
    instant: "41:06"
  - title: Estratégias de deploy
    instant: "42:32"
  - title: O software precisa estar preparado para essas estratégias
    instant: "51:05"
  - title: Conclusões
    instant: "52:11"
  - title: Recomendações
    instant: "53:28"

references:
  - title: With immutable infrastructure, your systems can rise from the dead
    author: Mike Johnston
    year: 2017
    type: post
    url: https://techbeacon.com/immutable-infrastructure-your-systems-can-rise-dead
  - title: An Introduction to Immutable Infrastructure
    author: Josh Stella
    year: 2015
    type: post
    url: https://www.oreilly.com/ideas/an-introduction-to-immutable-infrastructure
  - title: Immutable infrastructure with Docker and containers
    author: Jérôme Petazzoni
    year: 2015
    type: presentation
    url: https://www.slideshare.net/jpetazzo/immutable-infrastructure-with-docker-and-containers-gluecon-2015
  - title: Immutable Delivery
    author: John Willis
    year: 2015
    type: post
    url: https://theagileadmin.com/2015/11/24/immutable-delivery/
  - title: Amazon CTO details Cloud Computing commandments
    author: Sean Michael Kerner
    year: 2012
    type: news
    url: https://www.datamation.com/cloud-computing/amazon-cto-details-cloud-computing-commandments.html
  - title: Phoenix Server
    author: Martin Fowler
    year: 2012
    type: definition
    url: https://martinfowler.com/bliki/PhoenixServer.html
  - title: Snowflake Server
    author: Martin Fowler
    year: 2012
    type: definition
    url: https://martinfowler.com/bliki/SnowflakeServer.html
  - title: "Trash Your Servers and Burn Your Code: Immutable Infrastructure and Disposable Components"
    author: Chad Fowler
    year: 2013
    type: post
    url: http://chadfowler.com/2013/06/23/immutable-deployments.html
  - title: Are your servers PETS or CATTLE?
    author: Simon Sharwood
    year: 2013
    type: news
    url: https://www.theregister.co.uk/2013/03/18/servers_pets_or_cattle_cern/
  - title: Promise Theory and DevOps
    author: Derek Weeks
    year: 2017
    type: post
    url: http://blog.sonatype.com/promise-theory-and-devops

recommendations:
  - title: Cerrado por Fútbol
    author: Eduardo Galeano
    year: 2017
    type: book
    url: http://amzn.to/2BS4F1o
    who: Eriksen Costa
  - title: Frankenstein
    author: Mary Shelley
    year: 1818
    type: book
    url: http://amzn.to/2HJN10k
    who: Fernando Ike

# TODO: music credits.
media_credits:
  - description: Sítio arqueológico de Stonehenge
    name: Stonehenge
    type: picture
    page: "https://pixabay.com/en/stonehenge-architecture-history-1590047/"
    author: Walkers in The Way
    author_page: "https://pixabay.com/en/users/Walkerssk-1409366/"
    license: CC0
---

Infraestrutura imutável é uma forma de conceber a infraestrutura que provê estabilidade, eficiência e fidelidade para as
aplicações através do uso extensivo de automação. A ideia básica é que você cria e opera a sua infraestrutura usando o
conceito de imutabilidade: uma vez que você instancia alguma coisa, você nunca mais a altera. Ao invés disso, você aplica
mudanças substituindo-a com outra instância.

Esse episódio é uma prévia da palestra que o Fernando Ike dará no [Agile Trends 2018][#agile-trends-programacao] (28/03).

Por fim, também anunciamos o fim do podcast Na Estrada DevOps!

[#agile-trends-programacao]: http://agiletrendsbr.com/programacao-agiletrends-2018
