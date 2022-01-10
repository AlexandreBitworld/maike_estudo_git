# GIT E GITHUB

Guia Prático para iniciantes

### Instalação

https://git-scm.com/download

# SCENES

- [x] Você deseja criar pontos na história da produção do seu projeto
- [x] Você deseja verificar mudanças feitas no seu projeto
- [x] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito.
- [x] Você adiciona as novas funcionalidades ao seu projeto em produção
- [x] Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.

* `git init` // inicia a linha do tempo
* `git add` // adiciona ou atualiza mudanças para irem para a linha do tempoo
* `git commit` // adiciona um ponto na linha do tempo
* `git log` // visualiza os pontos na linha do tempo / commit
* `git status` // informa o estado das alterações do nosso projeto
* `git show` // apresenta determinado ponto na história
* `git branch` // gerenciar novas linhas do tempo
* `git checkout` // manipula as linhas do tempo
* `git merge` // unir linhas do tempo
* `git push` // envia alterações locais para o repositório remoto
* `git clone` // clonar um projeto / repositório
* `git pull` // puxa do repositório remoto

…or create a new repository on the command line
echo "# maike_estudo_git" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/AlexandreBitworld/maike_estudo_git.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/AlexandreBitworld/maike_estudo_git.git
git branch -M main
git push -u origin main

…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
