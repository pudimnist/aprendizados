> Passo a Passo - GitHub (Terminal)
1. (git init) = Iniciar o Repositório usando
2. (git add. ) = Pegar todos os arquivos alterados e colocar em Stage
3. (git commit -m "primeiro commit") = De fato o Primeiro Commit
4. (git status) = Para verificar o status dos itens alterados
    >> (git add "arquivo_x" & git restore "arquivo_x") = 
    add -> para "aprovar" a alteração 
    restore -> para descartar as alterações
5. (git diff & git log) = 
    diff -> Mostra a diferença dos arquivos não-commitados com os já commitados / 
    log -> Mostra todos os commits q foram feitos até então
6. (git restore "nome_arquivo") = Descarta todas as alterações do arquivo especificado
7. (git branch) = Mostra a branch atual
8. (git checkout -b nome_branch) = Criar nova branch com base na atual, copia as alterações para uma nova branch
9. (git merge nome_branch) = Vai mesclar as alterações feitas na outra branch com a master

> Criado o repositório no GitHub 
1. (git remote add origin https://github.com/pudimnist/"nome_do_repositorio".git)
2. (git push origin pedro) = Vai jogar os arquivos do código da branch especificada para o repositório remoto
3. (git pull origin pedro) = Vai pegar tudo que tem no repositório remoto e não tenho no meu projeto atual.
4. (git fetch) = Synca todas as alterações de todas as branchs, remotas e locais

> Problemas