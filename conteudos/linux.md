# 💻 Linux: Introdução ao sistema operacional

## O que é Linux?
[![LINUX](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](#)

O Linux, da mesma forma que o Windows (Microsoft) e o Mac OS (Apple), é um sistema operacional baseado em Unix criado para desktops, mas que também é usado em servidores, smartphones, tablets e outros tipos de dispositivos, incluindo caixas bancários.  Ao contrário de seus concorrentes mais famosos, o Linux não foi desenvolvido para fins comerciais e seu software e desenvolvimento são feitos em código aberto, o que significa que qualquer pessoa pode criar e distribuir aplicativos para ele.

## Qual a sua composição?
Linux é composto de um kernel, software criado para fazer a comunicação de outros programas e traduzi-los em comandos para a unidade de processamento e outros componentes eletrônicos. Para funcionar, porém, também é necessário aplicativos e bibliotecas específicas para eles.

## Como executar LINUX no WINDOWS com WSL 2
WLS trata-se de uma sigla para Windows Subsystem for Linux. Com o WSL, já era possível executar um ambiente Linux no Windows 10 para rodar utilitários e ferramentas do Linux.
Entre no site oficial da Microsoft, contendo o passo a passo para a instalação do WSL [clicando aqui!](https://docs.microsoft.com/pt-br/windows/wsl/install)

## Atalhos e Comandos no Terminal

| Função | Atalho / Comando |
| --- | --- |
| Determina uma saída no terminal | `echo` |
| Exibirá a saída com caracteres de formatação  | `echo -e` |
| Acessar o terminal Linux | `Ctrl + Alt + T` |
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
| Copiar um arquivo para outro diretório | `cp [nome do arquivo] [diretório]` |
| Específico para remover diretórios | `rmdir` |
| Excluir arquivos | `rm [nome do arquivo]` |
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

Para modificar um arquivo .txt, execute o `nano (nome do arquivo)` e você será redirecionado ao local GNU nano.

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
| Mostra o calendário do mês atual | `cal` |
| Mostra o calendário de todos os meses do ano desejado | `cal 'ano'` |
| Mostra a data atual | `date` |
| Exibe a função do comando | `whatis` |
| Busca por arquivos e exibe o caminho até o arquivo | `find` |
| Visualizar conteúdo do arquivo | `cat [nome do arquivo]` |
| Inverter linhas do conteúdo | `tac [nome do arquivo]` |
| Mostra as 10 primeiras linhas do arquivo | `head [nome do arquivo]` |
| Mostra as 10 últimas linhas do arquivo | `tail [nome do arquivo]` |
| Direcionar para um novo arquivo as linhas | `>`  (exemplo: `tail/head teste.txt > distros.txt`) |
| Direciona a entrada de um arquivo para a saída de um comando | `<` |
| Adicionar um novo arquivo as linhas | `>>`  (exemplo: `tail/head teste.txt >> distros.txt`) |
| Fazer uma busca por determinada palavra no arquivo | `grep [palavra]` |
| Usar dois comandos ao mesmo tempo | `usar o símbolo pipe` |
| Paginação de textos | `more` (exemplo: `cat teste.txt` pipe `more`) |
| Paginação de textos | `less` (exemplo: `cat teste.txt` pipe `less`) |
| Permite usar dois comandos e separar suas saídas no terminal | `&` (exemplo: `cat teste.txt & teste2.txt`) |
| Usado para que dois comandos sejam executados apenas se o primeiro for executado com sucesso | `&&` (exemplo: `cat teste.txt & teste2.txt`) |

## Exercícios Práticos de Revisão sobre arquivos .txt

1. **Crie uma pasta** de nome **Exercícios** e acesse a mesma
2. **Crie um arquivo** vazio de nome lista_nomes.txt
3. **Abra** o arquivo com o **editor nano**
4. **Digite** 20 nomes de pessoas conhecidas incluindo o seu, pulando linhas para cada nome inserido
5. **Salve** o arquivo
6. **Exiba os 10 primeiros** nomes da lista
7. **Exiba os 10 últimos** nomes da lista
8. **Procure** no texto o seu nome
9. **Crie** um arquivo chamado setembro.txt com a saída do comando cal
10. **Adicione o conteúdo** do arquivo setembro.txt ao arquivo lista_nomes.txt
11. **Exiba** o arquivo lista_nomes.txt com paginação
12. **Exiba** o caminho do arquivo setembro.txt
13. **Exiba** o tipo do arquivo lista_nomes.txt
14. **Exiba** a explicação do comando ls
15. **Renomeie** o arquivo lista_nomes.txt para arquivo.txt
16. **Limpe o terminal**
17. **Saia do terminal**

## Principais diretórios do Linux

| Descrição | Diretório |
| --- | --- |
| Binários principais dos usuários | /bin/ |
| Arquivos do sistema de Boot | /boot/ |
| Arquivos de dispositivos | /dev/ |
| Arquivos de configuração do sistema | /etc/ |
| Diretório dos usuários comuns do sistema | /home/ |
| Bibliotecas essenciais do sistema e os módulos do kernel | /lib/ |
| Diretório de montagem e dispositivos | /media/ |
| Diretório de montagem de dispositivos - mesmo que "media" | /mnt/ |
| Instalação de programas não oficiais da distribuição ou por conta do usuário | /opt |
| Armazena arquivos executáveis que representam comandos administrativos. Exemplo: shutdown | /sbin/ |
| Diretório para dados de serviços fornecidos pelo sistema | /srv/ |
| Diretório para arquivos temporários | /tmp/ |
| Segunda hierarquia do sistema, onde ficam os usuários comuns do sistema e programas | /usr/ |
| Diretório arquivos variáveis gerados pelos programas do sistema. Exemplo: logs, histórico da impressora, e-mail e cache | /var/ |
| Diretório do usuário root - O usuário root tem o total poder sobre o sistema. Podendo instalar, desinstalar, configurar | /root/ |
| Diretório virtural controlado pelo kernel | /proc/ |

## Outros comandos

| Descrição | Comando |
| --- | --- |
| Arquivo de informações do processador | cat/proc/cpuinfo |
| Exibir informações do processador | lscpu |
| Arquivo de informações da memória | cat /proc/meminfo |
| Exibir informações da memória física e virtual | free |
| Exibir informações detalhadas sobre o hardware | lshw |
| Exibir informações sobre hardware | lshw -short |
| Exibir o nome do kernel do sistema | uname |
| Exibir a versão do kernel | uname -r |
| Exibir a arquitetura do kernel | uname -m |
| Exibir a arquitetura do kernel | arch |
| Exibir todas as placas PCI conectadas | lspci |
| Exibir todos os dispositivos USB conectados | lsusb |
| Exibir o epsaço de cada arquivo e pasta no diretório pessoal consome no hd | du -h ~ |
| Reiniciar o sistema | reboot |
| Reinicia o sistema | shutdown -r |
| Desliga o sistema rapidamente | shutdown -h now |


## Redes, protocolos e interfaces de redes

### O que é Rede?
> Rede de computadores é um conjunto de equipamentos interligados de maneira a trocarem informações e compartilharem recursos, como arquivos de dados gravados, impressoras, modems, softwares e outros equipamentos (Sousa, 1999)

**Rede Wan**
**Wide Area Network** ou **World Area Network** é uma rede geograficamente distribuída.

**Rede Man**
**Metropolitan Area Network** é uma rede metropolitana que interligam várias redes locais.

**Rede Lan**
**Local Area Network** é uma rede local de uma forma geral em um único prédio ou campus.

### O que é **Protocolo**?

Protocolo é a "linguagem" usada pelos dispositivos de uma rede de modo que eles consigam se entender (Torres, 2004). 

**IP - Protocolo de Internet - Endereço IP:** números que identificam seu computador em uma rede
**ICMP - (Internet Control Message Protocol):** tem por objetivo prover mensagens de controle na comunicação entre nós
**DNS - Domain Name Server:** esse protocolo de aplicação tem por função identificar endereços IP e manter uma tabela com os endereços dos caminhos de algumas redes.

### O que é **Interface de Rede**?

Interface de rede é um software e/ou hardware que faz a comunicação em uma rede de computadores.
As interfaces de rede no Linux estão localizadas no diretório `/dev` e a maioria é criada dinamicamente pelos softwares quando são requisitadas.
Exemplo: eth0 - Placa de rede Ethernet - cabeada
A interface loopback é um tipo especial de interface que permite fazer conexões com você mesmo, com ela você pode testar vários programas de rede sem interferir em sua rede padrão, o endereço IP 127.0.0.1 foi escolhido para loopback.

## Comandos de redes e suas funções
Comando que faz parte do **pacote net-tools**.
Quando digitamos no terminal, uma mensagem é exibida, solicitando a instalação do pacote net-tools:

![image](https://user-images.githubusercontent.com/81873935/139723629-d40e8c76-2f0f-4594-8c41-fadb45345e3a.png)

Seguimos as instruções e instalamos o pacote net-tools através do comando `sudo apt installl net-tools`

| Função | Comando |
| --- | --- |
| Exibir informações sobre a interface de rede e IP | `ifconfig` |
| Semelhante ao executar como administrador do Windows | `sudo` |
| Exibir informações sobre o Host | `hostname` |
| Exibir endereço (IP) desse computador na rede | `hostname -I` |
| Exibir o número de endereço loopback do host | `hostname -i` |
| Exibir informações detalhadas sobre o usuário do computador de rede | `w` |
| Exibir informações curtas sobre o usuário do computador na rede | `who` |
| Como é o nome do usuário que estou logado na rede | `whoami` |
| Testar um host | `ping host` (ex: `ping: www.google.com` (para parar, Ctrl + Z)) |
| Mostrar informações sobre DNS | `dig` (ex: `dig www.google.com`) |
| Mostrar somente o endereço DNS | `dig host +short` (ex: `dig www.google.com +short`) |
| Traçar a rota da nossa rede local até determinado host | `traceroute host` |
| Saber informações sobre o site | `whois` (ex: `whois www.pudim.com.br`) |
| Exibir informações sobre o usuário do computador na rede | `finger` |

## Exercícios sobre redes

1. **Crie** um arquivo de aularedes.txt
2. **Exiba o número de IP** da rede no terminal
3. **Adicione** a saída do comando anterior no arquivo aula redes.txt
4. **Exiba o número de IP** Loopback no terminal
5. **Adicione** a saída do comando anterior ao arquivo aula redes.txt
6. **Exiba Informações DNS** sobre o host www.pudim.com.br
7. **Adicione** a saída do comando anterior ao arquivo aula redes.txt
8. **Exiba Informações do Usuário** logado na rede
9. **Adicione** a saída do comando anterior ao arquivo aula redes.txt
10. **Execute um teste no host** www.pudim.com.br com 6 pacotes
11. **Adicione** a saída do comando anterior ao arquivo aula redex.txt
12. **Trace a Rota** do seu computador até o host www.pudim.com.br
13. **Adicione** a saída do comando anterior ao arquivo aula redes.txt
14. **Exiba Informações sobre Interfaces de Rede e Endereços IP** no terminal 
15. **Adicione** a saída do comando anterior ao arquivo aula redes.txt
16. **Limpe** o terminal
17. **Imprima** o arquivo aularedes.txt com paginação no terminal
