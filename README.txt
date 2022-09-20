
# Intialize repository	  # Remove repository
  $ git init			        $ rm -rf .git

# Check files status (Staged, Unstaged)
  $ git status

# Prepara o arquivo (Staged)
  $ git add .

# Confirm (commit) all (-a) all files with a message (-m)
  $ git commit -a -m

# Link the local repository with github repository
  $ git remote add origin git@github.com:Casanova369/git-tutorial.git

# Name the main branch
  $ git branch -M main

# Push files to remote repository
  $ git push -u origin main

# Local branches management
  Read   - $ git branch -a
  Delete - $ git branch -d <branch-name>
  Create - $ git branch -M main

# remote branches management
 $ git branch -r

# Origin management
 List   - $ git remote
 Delete - $ git remote rm origin
 Create - $ git remote add origin <HTTPS> or <SSH>
