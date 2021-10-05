# Comandos Git

## Configuração

- As configurações do GIT são armazenadas no arquivo **.gitconfig** localizado dentro do diretório do usuário do Sistema Operacional, que por sua vez o arquivo é oculto, logo, é necessário habilitar a opção ` Itens Ocultos ` no campo  menu da pasta de arquivo.



- Configuração inicial:
  - informar nome do usuário:
    - `git config --global user.name "informe o nome do usuário."`
  - informar o e-mail:
    - `git config --global user.email "Informe o e-mail."	
  - Informar arquivos a serem ignorados (Caso tenha arquivos executáveis, a ser exportados no github é importante habilitar.)
    - `git config --global core.excludesfile ~/.gitignore`

## Repositório Local

- Criação de novo repositório
  - `git init`
- Verificar status dos arquivos ou diretório
  - `git status`
- Adicionar todos os arquivos do diretório
  - `git add .`
- Adicionar um determinado diretório
  - `git add Nome do diretorio.md`
- Adicionar um determinado arquivo específico
  - `git add Nome-do-arquivo.md`

- Caso o arquivo esteja listado no .gitignore e deseja adicionar
  - `git add -f nome-do-arquivo-gitignore.txt`

## Comitar Arquivos ou Diretório

- Comitar um determinado arquivo

  - `git commit arquivo.txt`

- Comitar informando uma determinada mensagem

  - `git commit arquivo.txt -m "Escreva a mensagem"`

- Comitar vários arquivos

  - `git commit arquivo-1.txt arquivo-2.txt`

- Comitar tudo incluindo mensagem

  - `git commit -m "Insira a mensagem"`

  

