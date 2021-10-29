# 💻 Introdução ao Git e ao GitHub

## O que é Git? 
[![GIT](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](#)
> Git é um sistema de controle de versão de arquivos. Através deles podemos desenvolver projetos na qual diversas pessoas podem contribuir simultaneamente no mesmo, editando e criando novos arquivos e permitindo que os mesmos possam existir sem o risco de suas alterações serem sobrescritas.

## O que é Git Hub? 
[![GITHUB](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](#)
> GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. Ele permite que programadores, utilitários ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo.

## Instalação do Git
[![GIT](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](#)
https://git-scm.com/downloads

| **Função** | **Comando** |
| --- | --- |
| Configurar o nome de usuário | git config --global user.name |
| Configurar o email do usuário | git config --global user.email email@email.com.br |

## Navegação básica no terminal
[![GIT](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](#)

| **Função** | **Windowns** | **Linux** |
| --- | --- | --- |
| Inicializando o versionamento no respectivo diretório | git init | git init |
| Listar as pastas  | cd | cd |
| Exibir o que tem dentro da pasta | dir | ls |
| Criar novos diretórios/pastas | mkdir | mkdir |
| Envia as modificações para o repositório remoto | git push origin | git push origin |
| Puxa alterações do repositório remoto | git pull origin | git pull origin |
| Seleciona um repositório existente e cria um clone ou cópia do repositório de destino | git clone | git clone |
| Excluir o documento / repositório | del (para documentos) / rmdir /S /Q (para repositório) | rm -rf |
| Verifica o status do repositório | git status | git status |
| Trackear o que não foi trackeado, inserir tudo | git add * | git add -A |
| Para commitar e comentar | git commit -m | git commit -am | (
| Lista de commits | git log | git log |
| Adicionar um repositório remoto | git remote add origin | git remote add origin
| Desfazer alterações | git reset (--soft / --mixed / --hard) | git reset (--soft / --mixed / --hard) |
| Mudar a branch atual | git checkout | git checkout |
| Aplica merge em branches | git merge nome-branch (precisa estar na branch de destino) | git merge nome-branch |
| Deleta uma branch local | git branch -D nome-branch | git branch -d nome-branch |
| Deleta todas as branch que não se encontram no repositório remoto | git branch --merged ## | git branch --merged ## |
| Checar o que houve nas alterações | git diff | git diff --name only |
| Criar arquivos sem conteúdo | echo > | touch |
