# Criando nova branch pelo terminal

Comando necessario para a criação de uma nova branch via terminal

`git checkout -b (nome-branch)`

    Este comando vai criar e já trocar para essa nova branch.

Verificar/ listar quantas branchs têm:

`git branch`

Alternar entre as branchs

`git checkout nome-branch-que-quero`

Para criar a branch pelo github:

1. Acessar o repositório
2. Ir na sessão de listagem das branchs
3. Inserir o nome da nova branch
4. Confirmar a criação dessa nova branch

Caso queira excluir uma branch pelo github:

1. Vá na sessão de listagem de branchs
2. Clique no ícone da lixeira para realizar a exclusão dessa branch

Aula 05: Fazendo merge local

1. Faça checkout na branch master
2. Faça um `git pull` para garantir que estará sincronizada com o repositório remoto
3. Dê o `git merge nome-da-branch-que-sera-mergeada`
4. `git status`
5. `git push`
