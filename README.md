# Git e Github

`Projeto criado para instruir os alunos do programa devstart, quanto a utilização do git e github. Utilizaremos este repositório para salvar dicas e comandos úteis do git e também da plataforma github.`

>#
>## Funcionalidades básicas
>
> *Configura o usuário*
>
>**`git config --global user.name "nome"`** 
>
>*Configura e-mail do usuário*
>
>**`git config --global user.email "email"`** 
>
>*Inicia um repositório vazio*
>
>**`git init`** 
>
>*Clona um repositorio existente*
>
>**`git clone "endereço do repositorio"`**
>
>*mostra os arquivos que podem ser comitados no repositorio local*
>
>**`git status`**
>
>*Prepara o arquivo a ser comitado*
>
>**`git add "nomedoarquivo.formato"`**
>
>*Prepara todos os arquivos para serem comitados*
>
>**`git add .`**
>
>*Remove o arquivo a ser comitado*
>
>**`git rm --cached "nomearquivo.formato"`**
>
>*Adiciona um commit*
>
>**`git commit -m "mensagem do commit"`**
>
>*Mostra o histórico de commits*
>
>**`git log`**
>
>*Envia o commit para o servidor*
>
>**`git push`**
>#
>## Ramificação e mesclagem
> *Lista todas as branch's*
>
>**`git branch`**
>
> *Cria uma branch*
>
>**`git branch "nome da branch"`**
>
> *Cria e acessa a branch*
>
>**`git checkout -b "nome da branch"`**
>
> *Deleta a branch*
>
>**`git branch -d "nome da branch"`**
>
> *Guarda as edições atuais*
>
>**`git stash`**
>
> *Lista as edições guardadas*
>
>**`git stash list`**
>
> *Salva alterações sem commit*
>
>**`git stash –include-untracked`**
>#
>## outros
>
> *Mostra o repositório remoto selecionado*
>
>**`git remote`**
>
> *Mostra repositório de origem*
>
>**`git remote -v`**
>
>*inverte as mudanças de um commit e gera um novo commit*
>
>**`git revert "4 primeiros dígitos do hash do commit"`**
>#
>## Autor
>
>[Elivandro](https://www.github.com/Elivandro/)
>#