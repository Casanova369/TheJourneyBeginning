
# Inicializar o Repositorio	  # Finalizar Repositório
  $ git init			        $ rm -rf .git

# Verifica o estado do arquivo (Staged, Unstaged)
  $ git status

# Prepara o arquivo (Staged)
  $ git add .

# Confirma (commit) todos -a (all) arquivos com uma mensagem -m (message)
  $ git commit -a -m

# Link the remote directory with github repository
  $ git remote add origin git@github.com:Casanova369/git-tutorial.git

# Nomeando o ramo principal
  $ git branch -M main

# Envia o código atual para o repositorio remoto
  $ git push -u origin main