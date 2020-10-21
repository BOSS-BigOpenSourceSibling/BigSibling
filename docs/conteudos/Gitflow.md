# Git e GitFlow: Guia de Estudo

## Live BOSS

Não viu nossa live? link em breve

Veja a apresentação utilizada na live nesse [link](https://docs.google.com/presentation/d/1Cyx6wL-Pn7SBAA-paIh8MWnOEdW0DFRlBuVHkQKG8sg/edit?usp=sharing)

## Como usar o git de forma colaborativa (Open Source)

Antes de iniciarmos com GitFLow existem outros conceitos de Git que são importantes para que você possa trabalhar em projetos de forma colaborativa. São eles: branch e merge.

### Branch

A tradução livre para "branch" é ramo. De forma simples um branch é um ramo criado com base no último commit da sua branch base.

É importante lembrar que as mudanças feitas em um branch não afetam outro branch, então eles são bem indepentes.

Uma boa forma de aprender um pouco mais e de forma visual como funcionam os branchs é utilizar o [Learn Git Branching](https://learngitbranching.js.org/?locale=pt_BR).

#### Comandos

Uma forma de criar um novo branch é utilizando o comando a partir do branch base:

`$ git checkout -b <nome-do-branch>`

Outra forma é utilizando:

`$ git branch <nome-do-branch> <branch-base>`

### Merge

O merge é uma mesclagem do que está sendo desenvolvido na branch com a branch base.

#### Comandos

Para fazer um merge você precisa estar no branch o que deseja "receber" as modificações, ou seja, o novo branch. Então considerando que você está no branch certo, utilize o seguinte comando:

`$ git merge <nome-do-branch>`

Para saber mais sobre Git Merge clique [aqui](https://www.atlassian.com/br/git/tutorials/using-branches/git-merge#:~:text=A%20mesclagem%20%C3%A9%20o%20jeito,integre%20em%20um%20%C3%BAnico%20branch.).

### GitFlow 

O GitFlow é um modelo de fluxo de trabalho baseado em branches.

Nesse modelo cada branch possui um papel e regras que definem como será sua interação com os outros branches.

Temos os seguintes branches:
* branch principal: essa é, como o nome diz, o branch principal do projeto. Nele é armazenado o histórico do lançamento oficial.
* branch de desenvolvimento: é onde os recursos desenvolvidos são integrados quando finalizados.
* branch de recurso: cada recursos novo desevolvido na aplicação é deve ser feito em um branch de recurso.
* branch de lançamento: quando o branch de desenvolvimento adquire recursos suficientes para um lançamento se cria uma ramificação a partir do branch de desenvolvimento.
* branch de manutenção: esse tipo de branch é utilizado para corrigir com rapidez lançamentos de produção, em inglês são chamados de hotfix.

Para entender melhor como funciona o GitFlow acesse [esse artigo](https://www.atlassian.com/br/git/tutorials/comparing-workflows/gitflow-workflow).

### Fork

Um fork é uma cópia de um repositório existente. Ao fazer um fork você faz uma cópia completa do repositório que deseja para o seu perfil, então você pode fazer experieências à vontade sem comprometer o projeto principal.

Para saber mais sobre Fork clique [aqui](https://docs.github.com/pt/github/getting-started-with-github/fork-a-repo).

### Pull Request

Pull requests são alterações propostas em um repositório enviadas por um usuário e que são aceitas ou rejeitadas pelos colaboradores do repositório. As pull requests têm um fórum próprio de discussão.

Para entender melhor sobre Pull Request acesse o [Glossário do GitHub](https://docs.github.com/pt/github/getting-started-with-github/github-glossary#).

## Links

* [BOSS - Semana 3: Git e GitFlow](https://docs.google.com/presentation/d/1Cyx6wL-Pn7SBAA-paIh8MWnOEdW0DFRlBuVHkQKG8sg/edit?usp=sharing)
* [Learn Git Branching](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Sobre-Controle-de-Vers%C3%A3o)
* [Git Branch](https://www.atlassian.com/br/git/tutorials/using-branches)
* [Git Merge](https://www.atlassian.com/br/git/tutorials/using-branches/git-merge#:~:text=A%20mesclagem%20%C3%A9%20o%20jeito,integre%20em%20um%20%C3%BAnico%20branch.)
* [Fluxo de trabalho: GitFlow](https://www.atlassian.com/br/git/tutorials/comparing-workflows/gitflow-workflow)
* [Fork - Bifurcar um repositório](https://docs.github.com/pt/github/getting-started-with-github/fork-a-repo)
* [Glossário do GitHub](https://docs.github.com/pt/github/getting-started-with-github/github-glossary#)

