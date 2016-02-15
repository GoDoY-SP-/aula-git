# aula-git
Repositório para testes das aulas GIT

Fase1 - Passo a passo para criação do README
--------------------------------------------

```
1-Criar repositório remoto pelo GITHUB
2-Criar pasta local "aula-git"
3-Iniciar o GIT dentro da pasta com o comando "git init"
4-Editar o arquivo de configuração local ".git/config" colocando os dados de usuário GITHUB
5-Baixar o conteúdo remoto com o comando "git pull origin master"
6-Editar o arquivo "README.md"
7-Verificar o arquivo alterado com "git status"
8-Adicionar a alteração em stage para commit com "git add README.me"
9-Verificar novamente as alterações com "git status"
10-Commitar as alterações com "git commit -m 'Alterações no README'"
11-Verificar novamente as alterações com "git status"
12-Enviar alterações para branch remota com "git push origin master"
```

Fase2 - Criar TAGs
--------------------------------------------

```
1-Criar TAG 0.1.0
2-Editar o arquivo "README.md"
3-Adicionar a alteração em stage para commit com "git add README.me"
4-Commitar as alterações com "git commit -m 'Novas alterações no README'"
5-Enviar alterações para branch remota com "git push origin master"
6-Criar TAG 0.1.1 com o comando "git tag -a v0.1.1 -m 'Versão 0.1.1'"
7-Enviar TAG para o repositório remoto com o comando "git push origin master --tags"
```