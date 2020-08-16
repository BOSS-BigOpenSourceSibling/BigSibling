# Git: Guia de Estudo

O Git é um sistema open source de controle de versão distribuído. Tá, mas o que é “controle de versão”?

Controle de versão é um sistema que registra alterações em um arquivo ou conjunto de arquivos ao longo do tempo para que você possa lembrar versões específicas mais tarde. 

Existem Sistemas Locais de Controle de Versão, Sistemas Centralizados de Controle de Versão e Sistemas Distribuídos de Controle de Versão. O Git é um sistema de controle de versão distribuído e para saber mais sobre você pode acessar a documentação oficial por esse [link](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Sobre-Controle-de-Vers%C3%A3o).

Com o Git você duplica localmente o repositório, ou seja, cada clone é um backup completo de todos os dados.

## Instale
Para instalar o Git basta escolher seu sistema operacional nesse [link](https://git-scm.com/downloads) e seguir o passo-a-passo.

## Alguns Comandos
Configurar o git no seu computador
Para configurar o nome de usuário que irá aparecer em seus commits:

`$ git config --global user.name "[nome]"`

Para configurar o e-mail do seu usuário:
$ git config --global user.email "[endereco-de-email]"
Criar repositórios
Para criar um repositório local:

`$ git init [nome-do-projeto]`

Para clonar um projeto:

`$ git clone [url]`

Comando básicos
Para listar todos arquivos novos ou modificados a serem commitados:

`$ git status`

Para adicionar um ou mais arquivos para a serem commitados:

`$ git add [arquivo]`

Para gravar os arquivos de forma definitva no histórico de versão:

`$ git commit -m "[mensagem descritiva]"`

Para listar todas branches locais do repositório atual:

`$ git branch`

Para lsitar o histórico de versão do branch atual:

`$ git log`

Para conhecer mais comandos do git acesse a [Folha de Dicas de Git](https://github.github.com/training-kit/downloads/pt_BR/github-git-cheat-sheet.pdf).

# Links

* [BOSS - Semana 1: Git](https://docs.google.com/presentation/d/1OVJmilgqgsMS_fEqDt0WkvUqc2x9kklASQXG8Hw9BBM/edit?usp=sharing)
* [Controle de Versão](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Sobre-Controle-de-Vers%C3%A3o)
* [Documentação do Git](https://git-scm.com/docs)
* [Folha de Dicas de Git](https://github.github.com/training-kit/downloads/pt_BR/github-git-cheat-sheet.pdf)
* [Instalação do Git](https://git-scm.com/downloads)
* [Mais opções de instalação](https://www.hostinger.com.br/tutoriais/git-gui/)