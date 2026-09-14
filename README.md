Crie uma pasta para o projeto
mkdir "meu-projeto"
Inicialize o git
git init
Crie ou coloque seus arquivos na pasta
Por exemplo, você pode criar um README.md
touch README.md
Adicione os arquivos ao Git
git add .
Faça o primeiro commit
git commit -m "Primeiro commit"
Crie o repositório no GitHub
meu-projeto
Conecte o Git local ao GitHub
git remote add origin https://github.com/SEU-USUARIO/meu-projeto.git
Defina a branch principal como main
git branch -M main
Envie o projeto para o GitHub
git push -u origin main
Crie a develop
git switch -c develop
Faça uma alteração
code README.md
Envie a develop para o GitHub
git push -u origin develop
Como mesclar develop na main
Faça o merge
git merge develop
Envie a main atualizada
git push origin main
