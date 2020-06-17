# Projeto WS-Git

Feito na live do dia 17/06/20 para os bolsista do [GESAD](http://www.uece.br/gesad/) da UECE para treinamento das funcionalidades que o Git e o GitHub podem proporcionar.

## Alunos Presentes

- [Éricson Moreira](https://github.com/ericsonmoreira).
- [Rebeca Teófilo](https://github.com/rebecateofi).
- [Naty Aragão](https://github.com/natysls).
- [Cecília Hélen](https://github.com/CeciliaHelen)
- Joao Felipe.

## Principais comandos do Git

Comandos inicais do git:

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

git config --global user.email "OUR_EMAIL" # configiração para o email do user.

git config --global user.name "OUR_NAME" # configiração para o nome do user.

git clone "URL_GITHUB" # clona o remositório remoto na seu computador.

git push origin HEAD:page_home # comando para dar um push do HEAD para a branch

git push  <REMOTENAME> <LOCALBRANCHNAME>:<REMOTEBRANCHNAME> # link para referência abaixo.
```

## Links de Referências/Importantes

- [Link de refência](https://help.github.com/pt/github/using-git/pushing-commits-to-a-remote-repository).
- [Documentação do Git](https://git-scm.com/docs).
- [Como fazer um README.md "bonitão" :blush:](https://medium.com/@raullesteves/github-como-fazer-um-readme-md-bonit%C3%A3o-c85c8f154f8).
- [Video aulas de Git/GitHub](https://www.youtube.com/playlist?list=PLbEOwbQR9lqzK14I7OOeREEIE4k6rjgIj).
