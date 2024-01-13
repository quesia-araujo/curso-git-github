# Notas de aula referente ao módulo 04

## Trabalhando com projetos de outras pessoas

### Aula 01: Fazendo um fork

O fork é feito a partir da interface do github.

1. Foi feito o fork do repositório da professora Kamila.
2. Fiz o clone desse fork pra a minha máquina.
3. Feito o clone, criei uma branch para fazer alteração no readme
adicionei e commitei as alterações que fiz.
4. Após isso, fiz um push origin master, como solicitação de pull request.

### Aula 02: Mantendo seu projeto atualizado com o projeto principal

- **Atualizando o seu fork pelo github**

    1. No repositório forkado se houver commits atrás vá em _compare_.
    2. Clique no link _switching the base_.
    3. Click em _Create pull request_, caso não haja conflitos.
    4. Crie um titulo, exemplo: _Atualizando meu fork_.
    5. Aparecerá a solicitação do pull request.
    6. Faça o _merge pull request_.

- Comando para atualizar o seu fork com o repositório de origem

    1. Digite: `git remote add upstream <link-do-repositorio`
    2. Depois: `git fetch upstream`
    3. Vá para a branch master
    4. Digite: `git rebase upstream/master`.

### Aula 03: Criando sua branch para enviar as suas alterações

git checkout -b add-meu-user-quesia

faz as alterações.
git status
git add .
git commit -m "atualizando arquivo para pull request"
git push
apare que é preciso configurar a upstream
git push --set-upstream origin add-meu-user-quesia
Ele sugere que crie uma pullrequest, é só seguir o link.
Abre a pagina do github "open a pull request".

### Aula 04: Criando sua primeira pull request

git checkout -b
git pull
git status
git add
git commit
configura upstream
abre link

Adicionar o Title
Adicionar revisor -Reviewers
Assignees - Responsável  pela pull request (eu mesma).
Adicionar comentário,  pq está encaminhando a pr.
Abra a pull request

Revião da pull
ir em pull requests
files changed
Repetir a quantidade de vezes necessária: ir no mais, adicionar comentário de revisão (add review comment).
Finish your review
selecionar opções: comment e request changes.
submit review

Corrigindo a revisão
duas opções: pelo github ou pela máquina.

pela máquina local:
Faz os ajustes
git status
git add .
git commit
git push
comentar que é ajuste

Revisão
files changed
approve e comentario
submite review
Merge pull request
deletar branch
