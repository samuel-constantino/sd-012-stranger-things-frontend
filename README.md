# Boas vindas ao repositório frontend do projeto de Deploy - Stranger Things!

Aqui você vai encontrar os locais para colocar suas repostas relativas aos requisitos de frontend.

**Lembre-se**: coloque as respostas apenas dos requisitos que contém o seguinte direcionamento:

  - Adicione os comandos utilizados, de maneira sequencial, ao README do frontend.

**Nota**: Este direcionamento está presente no [repositório](https://github.com/tryber/sd-012-stranger-things) em que os requisitos do projeto são destrinchados.


7. Verifica as variáveis de ambiente do frontend

  - Cria arquivo .env e adiciona as variáveis de ambiente (url e timeout)

  - Substitui os valores da url e timeout pelas variáveis de ambiente.

8. Verifica se foi feito o deploy do frontend no Heroku

  - Cria app:
    - heroku create samuel-constantino-ft --buildpack mars/create-react-app

  - Configura as variáveis de ambiente no heroku (pelo site)

  - Deploy:
    - git push heroku master

9. Verifica os multi-ambientes e modo de desenvolvimento.

  - Renomia repositorio remoto
    - git remote rename heroku development

  - Adiciona paragrafo indicador de ambiente de desenvolvimento

  - Cria app (produçao)
    - heroku create samuel-constantino-pd --remote production --buildpack mars/create-react-app

  - Remove paragrafo indicador de desenvolvimento e faz deploy
    - git push production master

