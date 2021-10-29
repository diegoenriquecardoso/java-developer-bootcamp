# 💻 Linux: Introdução ao sistema operacional

## O que é Linux?
[![LINUX](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](#)
> O Linux, da mesma forma que o Windows (Microsoft) e o Mac OS (Apple), é um sistema operacional baseado em Unix criado para desktops, mas que também é usado em servidores, smartphones, tablets e outros tipos de dispositivos, incluindo caixas bancários.  Ao contrário de seus concorrentes mais famosos, o Linux não foi desenvolvido para fins comerciais e seu software e desenvolvimento são feitos em código aberto, o que significa que qualquer pessoa pode criar e distribuir aplicativos para ele.

## Qual a sua composição?
> Linux é composto de um kernel, software criado para fazer a comunicação de outros programas e traduzi-los em comandos para a unidade de processamento e outros componentes eletrônicos. Para funcionar, porém, também é necessário aplicativos e bibliotecas específicas para eles.

## Como executar LINUX no WINDOWS com WSL 2
> WLS trata-se de uma sigla para Windows Subsystem for Linux. Com o WSL, já era possível executar um ambiente Linux no Windows 10 para rodar utilitários e ferramentas do Linux.
> Entre no site oficial da Microsoft, contendo o passo a passo para a instalação do WSL [clicando aqui!](https://docs.microsoft.com/pt-br/windows/wsl/install)

## Atalhos e Comandos no Terminal

| Função | Atalho / Comando |
| --- | --- |
| Cancelar o comando atual em funcionamento | `Ctrl + C` |
| Pausar o comando atual, em primeiro plano ou segundo plano. | `Ctrl + Z` |
| Fazer o logout da sessão atual | `Ctrl + D` |
| Apagar uma palavra na linha atual | `Ctrl + W` |
| Apagar a linha inteira | `Ctrl + U` |
| Busca um comando recente | `Ctrl + R` |
| Repetir o último comando | `!!` |
| Listar diretórios e arquivos | `ls` |
| Opção de lista longa com detalhes | `ls -l` |
| Listar outro diretório que não o atual | `ls dir` |
| Exibir histórico de comandos | `history` |
| Criar diretórios | `mkdir [nome do diretório]` |
| Remover diretórios com a opção -r | `rm -r` |
| Mudar o diretório atual para outro | `cd dir` |
| Mudar para o diretório raiz / | `cd /` |
| Mudar para o diretório pessoal (home) | `cd ~` |
| Retornar ao diretório anterior | `cd ..` |
| Exibir o arquivo de ajuda de um comando | `--help` |
| Exibir o manual do comando | `man [comando]` |
| Renomear um diretório ou arquivo | `mv [antigo nome] [novo nome]` |
| Mover um diretório para o diretório pessoal | `mv dir/ ~` |
| Criar aquivos vazios no Linux | `touch [nome do arquivo]` |
| Fazer cópia de um arquivo para outro diretório | `cp [nome do arquivo] [diretório]` |
| Específico para remover diretórios | `rmdir` |
| Remover arquivos | `rm [nome do arquivo]` |
| Mostra o calendário do mês atual | `cal` |
| Mostra o calendário de todos os meses do ano desejado | `cal 'ano'` |
| Mostra a data atual | `date` |
| Limpar o terminal | `clear` |
| Finalizar a sessão do terminal | `exit` |

## Exercícios Práticos de Revisão:

1. Abra o Terminal no Linux
2. **Crie uma pasta** de nome "Ubuntu" dentro da pasta **Documentos**
3. Mova a pasta **Ubuntu** para o diretório pessoal
4. Crie um **arquivo vazio** de nome teste.txt dentro da **pasta Ubuntu**
5. **Renomeie** o arquivo como linux.txt
6. **Crie uma cópia** deste arquivo na pasta **Downloads**
7. **Exiba todos os comandos** digitados no terminal
8. Execute a **ajuda** do comando ls
9. Execute o **manual** do comando mv
10. **Pare** a execução do manual
11. **Saia do terminal** utilizando sequência de teclas
12. **Exclua** a pasta Ubuntu
13. **Exclua** o arquivo linux.txt
14. **Limpe** o terminal
15. Utilize o comando para **sair** do terminal

## Lidando com arquivos .txt

> Para modificar um arquivo .txt, execute o `nano (nome do arquivo)` e você será redirecionado ao local GNU nano.

![image](https://user-images.githubusercontent.com/81873935/139365299-6a3f759d-b97e-4002-a4d6-53692149281a.png)

| Função | Atalho |
| --- | --- |
| Justificar o texto | Ctrl + J |
| Desfazer a última ação | ALT + U |
| Refazer a última ação | ALT + E |
| Marcar texto | ALT + A |
| Copiar o texto | ALT + 6 |
| Colar o texto | CTRL + U |
| Verificar ortografia | CTRL + T |
| Substituir termos | CTRL + / |
| Salvar o arquivo | CTRL + O |
| Sair do nano | CTRL + X | 
| Visualizar conteúdo do arquivo | `cat [nome do arquivo]` |
| Inverter linhas do conteúdo | `tac [nome do arquivo]` |
| Mostra as 10 primeiras linhas do arquivo | `head [nome do arquivo]` |
| Mostra as 10 últimas linhas do arquivo | `tail [nome do arquivo]` |
| Direcionar para um novo arquivo as linhas | >  (exemplo: `tail/head teste.txt > distros.txt`) |
| Fazer uma busca por determinada palavra no arquivo | `grep [palavra]` |
