# Notas de aula referentes ao Módulo 2

## Aula 01: Criando um repositório Local

Criando uma pasta:

    `mkdir nome-da-pasta`

Listando os arquivos

    `ls`

Abrindo a pasta:

    `cd nome-da-pasta`

Abrindo o editor de codigo

    `code .`

Abro terminal no vscode.
Verificar as configurações de nome de usuário e email:

    git config –list

Iniciando git no diretório

    git init

Adicione pastas/arquivos
verifique o status do git

    git status

## Aula 02: Conectando seu repositório local com um remoto no GitHub

Verificando se já existe repositório remoto

    git remote -v

adicionando repositorio remoto

    git remote add origin link-do-repositorio

## Aula 03: Clonando um repositório já existente

Clonando um repositório
abrindo pasta anterior

    cd ..

Criando uma nova pasta

    mkdir teste-clone

Abrindo a pasta criada

    cd teste-clone

Clonando repositório remoto

    git clone link-do-repositorio

## Aula 04: Comandos mais utilizados - git status

criando e modificando novos arquivos

    git status

## Aula 05: Comandos mais utilizados- git status

### git status

**verifica o status dos arquivos e paastas dentro do nosso repositório.**

### git add

#### `git add .`

**adiciona todos os arquivos para a esteira de commit.**

#### fit add [caminho do arquivo]

**adiciona um arquivo em específico.**

## Aula 06: comandos mais utilizados - commmit

commitando os arquivos modificados
modificando mais arquivos e não commitando

## Aula 07: Comandos mais utilizados - git push e pull

### git push

(primeiro push):
git push --set-upstream origin master

### git pull

## Branchs

Criando uma branch pelo terminal.

Alternando para essa nova branch.

git checkout -b nome-branch
