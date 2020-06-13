# CURSO GIT

### Comandos
    
    git config --global user.name "nome"
    git config --global user.email "email"
    git config --global core.editor vscode
    git config --list

    git init - iniciar um repositorio
    touch <nome do arquivo> - criar um arquivo
    git add <nome do arquivo> - armazenando o arquivo em um local para que o git consiga observar quando é realizado o commit
        git add -A - faz a mesma coisa do anterior mas com todos arquivos 
    git commit -m "mensagem" - levar a alteração ate o repositorio
    git log - vizualizar pontos
    git status - estado do desenvolvimento (local atual, arquivos modificados, arquivos que não estao no ropositorios, etc)
    git show <numero do commit> - vizualizar dados do commit (sem numero mostra o ultimo)

    git branch <nome branch> - criar uma branch
    git checkout <nome branch> - entrar na branch
    git branch - vizualizar branchs

### 