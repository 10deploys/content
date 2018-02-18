# 10deploys content

Esse repositório contém o conteúdo do site do podcast [10deploys](https://10deploys.com).


## Configuração

A configuração desse site é baseada no tema `10deploys-theme`. Com o
[Docker Compose](https://docs.docker.com/compose/) instalado, execute:

    $ docker-compose run --service-ports site jekyll serve

Então, abra seu navegador no endereço `http://localhost`.


## Contribuições

Achou um erro? Basta abrir uma _pull request_ com a correção.

O formato para as mensagens de commit é o documentado pelo
[Tim Pope](https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html). Em resumo:

- Título com verbo tempo presente, limite de 50 caracteres
- Corpo opcional, com limite de 72 caracteres


## Licença

O conteúdo do site é publicado sob uma licença
[Creative Commons](https://creativecommons.org/licenses/by-sa/4.0/). Arquivos audivisuais podem ser publicados sob uma
licença diferente.

A licença do código-fonte é a [Apache License 2.0](https://choosealicense.com/licenses/apache-2.0/).
