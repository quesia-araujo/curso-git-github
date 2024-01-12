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
