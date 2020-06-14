# CURSO GIT

### Comandos
    
    git config --global user.name "nome"
    git config --global user.email "email"
    git config --global core.editor vscode
    git config --list

    git init: iniciar um repositorio
    touch <nome do arquivo>: criar um arquivo
    git add <nome do arquivo>: armazenando o arquivo em um local para que o git consiga observar quando é realizado o commit
        git add -A: faz a mesma coisa do anterior mas com todos arquivos 
    git commit -m "mensagem": levar a alteração ate o repositorio
        git commit -am "mensagem": add e commit
    git log: vizualizar commits
    git status: estado do desenvolvimento (local atual, arquivos modificados, arquivos que não estao no ropositorios, etc)
    git show <numero do commit>: vizualizar dados do commit (sem numero mostra o ultimo)

    git reset --soft <codigo do commit>: volta ao estado antes do commit com as modificações ainda preparadas
    git reset --mixed <codigo do commit>: volta ao estado antes do commit com as modificações não preparadas (precirará dar o add)
    git reset --hard <codigo do commit>: ignora tudo e volta no ponto

    git branch <nome branch>: criar uma branch
    git checkout <nome branch>: entrar na branch
    git branch: vizualizar branchs

    git diff: mostra alterçoes feitas 
    git diff --name-only: mostra o nome dos arquivos modificados
    git checkout HEAD -- <nome do arquivo>: descartar mudanças e manter somente um arquivo (HEAD branch atual // -- informa que tudo que vem depois é nome de arquivo)
    git checkout HEAD -- <nome do arquivo>: volta no estado anterior do arquivo
    
### 