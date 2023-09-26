OI, esse projeto ensina você a usar o git :)
<> git init
-> cria um repositório vazio sem versão
<<>> Initialized empty Git repository

<> git add ReadMe.md
-> chama o arquivo para a área de "aguardo"

<> git status
-> mostra os arquivos a serem comitados

<> git commit -m 'comentario'
-> comita o arquivo, o arquivo vai para o repositório local

<> git remote add origin https://github.com/manuuvillar/git-projeto.git
-> faz a conexão entre o repositório local com o repositório do git que se chama 'origin'

<> git push -u origin main
-> puxa os commits do repositorio local para o repositório do git

<> git add .
-> todos os arquivos da pasta vão para área de "aguardo"