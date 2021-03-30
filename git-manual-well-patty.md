{\rtf1\ansi\ansicpg1252\cocoartf1561\cocoasubrtf610
{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 #Para colunar e iniciar um projeto\
\
git clone <endere\'e7o do reposit\'f3rio conforme fornecido pelo gerenciador de reposit\'f3rios> \
\
O GIT CLONE \'e9 equivalente a:\
\
git init\
git remote add origin <https://github.com/wwagner33/test-git.git>\
git pull origin main #no caso do Github \'e9 MAIN mas poderia ser master\
\
# Criando um branch para cedar a feature\
\
git branch  #mostra todos os branchs locais\
git branch -a #mostra todos os brancos locais e remotos\
\
git checkout -b <minha_branch> #cria a \'e1rvore de arquivos em cima da nova branch\
\
\
# Criando um Pull Request para aceite dos novos commits da sua branch\
\
git add \'97all\
git commit -m \'93Bl\'e1 Bl\'e1 Black. Bem claro e objetivo\'94 \
\
 git pull origin main #para trazer c\'f3digo do  MASTER no GitHub. Se quiser trazer de uma branch, usar \'93origin nome_da-branch\'94\
git push origin minha_branch #manda para o remote criando a branch ou colocando numa branch existente\
\
# Para apagar a branch local ou remota\
\
##Branch local\
\
git branch -D <nome_da_branch> #deve sair do branch onde se est\'e1 para poder apagado. Use o git checkout para passear entre os branchs\
\
\
/##Branch remoto\
git push origin -d <nome_do_branch>\
\
\
#Para ver os brancos e se mover entre brancos\
\
## ver\
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0
\cf0 git branch  #mostra todos os branchs locais\
git branch -a #mostra todos os brancos locais e remotos\
\
##mover para um branch\
git checkout <nome_do_branch>\
\
\
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0
\cf0 \
#Fontes:\
\
https://blog.da2k.com.br/2015/02/04/git-e-github-do-clone-ao-pull-request/\
https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell\
\
\
\
}