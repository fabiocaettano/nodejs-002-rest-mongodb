# REST-API com Node e Moongoose


# Indice
* [Ambiente](## Ambiente)
* [Máquina Virtual](## máquina-virtual)
* [NVM](## NVM)
* [GIT](## GIT)

## Ambiente

1. Windows 10;
2. WSL;
3. UBUNTU 20.04;
4. Visual Studio Code;
5. Máquina Virtual

## Máquina Virtual

No serviço da Digital Ocean criar uma máquina virtual (Droplet).
Configuração:

1. Image: Ubuntu 20.04
2. Plano: Shared CPU - Basic
3. CPU Options: CPU Com 1 CPU e 1 GB de memória; 25 GB de SSD


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