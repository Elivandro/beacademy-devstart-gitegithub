# Git e Github

Projeto criado para instruir os alunos do programa devstart, quanto a utilização do git e github. Utilizaremos este repositório para salvar dicas e comandos úteis do git e também da plataforma github.

## Funcionalidades basicas

git config --global user.name "nome" (configura usuário)

git config --global user.email "email" (configura email de usuário)

git init (inicia um repositorio vazio)

git clone "endereçodorepositorio" (clona um repositorio existente)

git status (mostra os arquivos que podem ser comitados no repositorio local)

git add "nomearquivo.formato" (prepara o arquivo a ser comitado)

git add . (prepara todos os arquivos para serem comitados)

git rm --cached "nomearquivo.formato" (remove o arquivo a ser comitado)

git commit -m "mensagem do commit"  (adiciona um comit)

git log (mostra o historico de commits)

git push (envia o comit para o servidor)

## Ramificação e mesclagem

git branch (lista todas as branch's)

git branch "nomedabranch" (cria uma branch)

git checkout -b "nomedabranch" (cria e acessa a branch)

git branch -d "nomedabranch" (deleta a branch)

git stash (guarda as edições atuais)

git stash list (lista as edições guardadas)

git stash –include-untracked (salva alterações sem commit)

## outros
git remote (mostra o respositorio remoto selecionado)

git remote -v (mostra repositório de origem)

git revert <4 primeiros dígitos do hash do commit> (inverte as mudanças de um commit e gera um novo commit com o conteúdo invertido) 

## Autor

[Elivandro](https://www.github.com/Elivandro/)


