Ajuda no Git

Comandos (no git bash)
git --version: versão do Git instalado
git init: inicia um repositório Git vazio
    cria uma pasta .git na pasta selecionada
git add: adiciona o arquivo pro commit (o palco do Git)
git status: mostra o branch, o commit e os arquivos adicionados
git commit -m "nome do commit": titulo da commit
git --global config user.email "you@example.com"
git --global config user.name "Your Name"
    colocar a sua identidade padrão
    tira o --global para colocar essas informações apenas neste repositório

git branch -M "main"
    renomea a branch, ex: "Master" muda para "main"

~ Com o GitHub
git remote add origin <yourLink>
    faz a conexão do repositório do Git com o repositório do GitHub
git push -u origin main
    coloca o arquivo no repositório do GitHub
    