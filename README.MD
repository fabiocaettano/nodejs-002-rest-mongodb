# REST-API com Node e Moongoose


** [NVM](##NVM)
** [SSH](##SSH)
** [GIT](##GIT)

## SSH 

## NVM 

Instalar NVM no Ubuntu 20.04:

``` cli
curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash 
source ~/.bashrc
nvm install node
```

Visualizar a versão instalada:

``` cli 
nvm ls
```

Instalar outra versão:

``` cli
nvm install 12.18.3
```

Checar as versões disponiveis:

``` cli
nvm ls-remote
```

Checar a versão latest:

``` cli
nvm run --default --version
```

## GIT

Criar o repositório Git

``` cli
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/usuarioGit/rest-api-001.git
git push -u origin main
```