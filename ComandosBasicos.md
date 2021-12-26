
# Iniciar o git
> git init

# Clonar um repositorio
> git clone <endereço do repositorio a ser clonado>

# Verificar o status
> git status

# Listar os repositorios remotos
> git remote -v
> git remote

# Adicionar um arquivo expecifico
> git add <nome do arquivo>

# Adicionar todos arquivos
> git add .

# Comitar os arquivos do repositorio remoto
> git commit -m "aqui vai o comentário"
> git commit

# Apontar para um repositorio
> git remote add origin <endereço da localização>

# Atualizar o repositorio com a origem
> git pull
> git pull origin main

# Subir o arquivos commitados
> git push origin main

# Visulizar o histórico
> git log (comando "e" sair ou digitar ":q")

# Visualizar os logs de um arquivo ou diretório
> git log <nome de um diretorio>
> git log <nome de um arquivo>

# Visualizar os logs em uma linha
> git log --oneline

# Visualizar de forma grafica os logs 
> git log --graph

# Ferramenta gráfica no Windows
> gitk 

# Git RESET
- Reseta um determinado commit
> git reset <hash>
- Move a cabeça
> git reset <HEAD~1>

# Volta para index/o estado antes do commit
> git reset --soft HEAD~1

# Volta para untraked/o estado antes do add
> git reset --mixed  HEAD~1

# Reseta o commit apagando tudo
> git reset --hard HEAD~1

# Reverte criando um novo commit para um anterior
> git revert HEAD~1

# Listar configurações
> git config --global --list

# Commit bem estruturado
> git commit 

# Colocar outro editor padrão para o gitbash
> git config --global core.editor "code --wait"

# Remove uma configuração
> git config --global --unset <nome>