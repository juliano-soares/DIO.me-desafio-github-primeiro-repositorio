# Criar uma branch
> git branch <none da branch>

# Criar uma Branch e navega ate ela
> git checkout -b <nome da nova branch>

# Deletar branchs
> git branch -d <nome da nova branch>

# Alterar nome da branch estando dentro dela
> git branch -m <novo nome>

# Alterando o nome de uma branch qualquer
> git branch -m <nome atual> <novo nome>

# Navegar entre branchs
> git checkout <nome da branch>

# Unir branch com a master
> git merge <nome da branch>

# Listar as branchs
> git branch

# Mover entre branch sem lixo
- Cria um stash armazena o que esta fazendo
> git stash save "contexto"

- Listar o stash
> git stash list

- Adicionar mais arquivos ao stash
> git stash save "contexto"

- Retornar o que estava no stash
> git stash pop <numero da stash>

- Limpar o stash
> git stash clear

