### ...or create a new repository on the command line
### ...ou crie um novo repositório na linha de comando
echo "# gitdemo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:gioperrotta/gitdemo.git
git push -u origin main


### ...or push an existing repository from the command line
### ...ou envie um repositório existente a partir da linha de comando
git remote add origin git@github.com:gioperrotta/gitdemo.git
git branch -M main
git push -u origin main