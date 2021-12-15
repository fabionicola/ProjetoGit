Lea-me para saber algusn comandos do git.

segue atalhos do teclado para usar o git:

insert / ctrl+shift+v - colar

token de acesso: https://www.alura.com.br/artigos/nova-exigencia-do-git-de-autenticacao-por-token-o-que-e-o-que-devo-fazer?gclid=Cj0KCQiAweaNBhDEARIsAJ5hwbcShBUuZJ2dQ9giDTWQZBuHGA7hxbmL-m6Sh2W3KWlec-1decfi694aAv1UEALw_wcB

segue os comandos:

$git --version - comando git que mostra a versao do git instalada no computador

$clear - limpa a tela

$cd nome da pasta - comando para entrar dentro de uma pasta

$git init - inicializa um repositorio git vazio

$git branch -M "main" - muda o nome da branch principal para main

$git config --global user.name "nome do github" - configura o nome do github no computador

$git config --global user.email "e-mail do git hub" - configura o email de cadastro do git hub no computador

$git config --list - lista as configuraçoes do git

$git add - manda os arquivos para área de stage
        git add . - manda todos os arquivos da pasta para o stage
        git add nome_do_arquivo - manda o arquivo para o stage

$git log - lista as versoes

$git status -  mostra as mudanças a serem comitadas

$git commit -m ""(nome da mensagem do commit) - cria um commit do arquivo que esta na area de stage

$git remote add origin git@github.com:fabionicola/ProjetoGit.git (link do diretorio driado no github.com) - remote(conexão entre o repositorio local e o site) add (adicionar) origin (apelido/nome para o repositorio do github) link

$git remote -v - mostra se o projeto esta associado ao repositorio git

$git push -u origin main - empurrao dos commits no repositorio local para o repositorio no site / -u salva a referencia para na prossima vez so usar git push

$git remote remove origin - remove a origin salva

$git push - envia para o diretorio as alterações

$git checkout -b "nova-branch" - cria uma nova branch e ja vai para a nova branch
        - para enviar o arquivo no comando $git push -u origin main (alterar o main para o nome da nova-branch)

$git checkout main - volta para a main principal

$git merge nova-branch - mescla a branch criada para com a principal
        - para que esse comando funcione tem-se que estar na branch ao qual se deseja mesclar, no caso a main

$git clone link - link do repositorio a ser clonado no computador

$git pull - atualiza o projeto que esta no computador com o do repositorio

$git fork - 

$git pull request - 











