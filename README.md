# Projeto WS-Git

Comando inicais do git:

```bash
git init # inicia um repositório local.

git add . # prepara as alterações para o commit

git commit -m "sua mensagem aqui" # comando de commit. Essa mensagem serve para dar uma pequena explicação do que foi o commit

git remote add origin "url do repositório remoto aqui" # cria um "remote" do seu repositório remoto. "origin" é o nome desse remote (esse nome vc escolhe).

git push -u origin master # "empurou" o commit da branch master local para a branch master remota (lembre-se do remote que criamos).

git branch NOME-DO-BRANCH # como criar uma branch local.

git push origin NOME-DO-BRANCH # como dar um push usando o branch local recém criado para o remoto.

git checkout page_home # selecionar a branch que eu quero trabalhar

git branch # visualizar as branchs (inclusive a branch atual)

git remote -v # visualizar os remotes.

git log --oneline # mostra os commit. (--oneline -> para mostrar só em uma linha).

git reset # volta o commit.

git config --global user.email "OUR_EMAIL" # configiração para email do user.
```
