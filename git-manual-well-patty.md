# Para clonar e iniciar um projeto

> git clone <endereço do repositório conforme fornecido pelo gerenciador de repositórios

O GIT CLONE é equivalente a:

> git init
> 
> git remote add origin https://github.com/wwagner33/test-git.git
> 
> git pull origin main #no caso do Github é o MAIN mas poderia ser master

# Criando um branch para cedar a feature

> git branch  #mostra todos os branchs locais
> git branch -a #mostra todos os brancos locais e remotos

> git checkout -b <minha_branch> #cria árvore de arquivos em cima da nova branch


# Criando um Pull Request para aceite dos novos commits da sua branch

> git add --all
> git commit -m " texto bem claro e objetivo"

> git pull origin main #para trazer código do  MASTER no GitHub. Se quiser trazer de uma branch, usar "origin nome_da-branch"
> git push origin minha_branch #manda para o remote criando a branch ou colocando numa branch existente

# Para apagar a branch local ou remota

## Branch local

> git branch -D <nome_da_branch> #deve sair do branch onde se está, para este possa ser apagado. Use o git checkout para passear entre os branchs


##Branch remoto
> git push origin -d <nome_do_branch>


# Para ver os brancos e se mover entre brancos

## ver

> git branch  #mostra todos os branchs locais
> git branch -a #mostra todos os brancos locais e remotos

## mover para um branch
> git checkout <nome_do_branch>

# Para fazer merge com branchs locais
> git checkout main #ou o nome do master usado.
> 
> git merge <nome_do_branch>

# Para enviar para um remoto "staging"
git remote set-head $REMOTE_NAME $BRANCH #modifica o HEAD para o branch remoto
git branch -u <origin/<remoto> <testando-test> #Criei meu branch local

Alternativa:
git branch <nome_branch>

git checkout <nome_branch> #Vai para seu branch
git add --all
git commit -m "a frase fe comentário"
git pull
git push origin teste-branch
  
  # Para remover todos os itens que estão para ser dado commit
  git reset HEAD <file>

# Fontes:

https://blog.da2k.com.br/2015/02/04/git-e-github-do-clone-ao-pull-request
https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell
https://devconnected.com/how-to-push-git-branch-to-remote/
