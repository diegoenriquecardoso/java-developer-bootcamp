# 💻 Dominando IDE's Java

## O que é IDE?
[![IntelliJIDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)](#)
[![ECLIPSE](https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipse&logoColor=white)](#)
[![VSCODE](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)](#)

IDE, ou ambiente de desenvolvimento integrado, é um software que combina ferramentas comuns de desenvolvimento em uma única interface gráfica do usuário (GUI), facilitando o desenvolvimento de aplicações. 

Neste guia aprenderemos a instalar o *OpenJDK* no Linux, instalar o *Eclipse* e também aprenderemos a instalação di *Git*.

## 🐧 Instalação OpenJDK no Linux

O OpenJDK (Kit de Desenvolvimento Java Aberto) é uma  implementação gratuita e de código aberto da linguagem de programação  Java.  A implementação está licenciada sob a GNU General Public License  (GPL) com uma exceção de vinculação. JDK = JRE + JVM

1. Abra o terminal e vamos verificar se temos o Java instalado:

`java -version`

2. Para instalar o openJDK-11, digite no terminal:
<em>A versão mais atual LTS é do Java 11, que terá seu suporte  estendido até Setembro de 2022. Este tipo de suporte iniciou no Java 8  que será mantido até 2023.</em>

`sudo apt-get install openjdk-11-jdk`

3. Confirme se realmente foi instalado com sucesso:

`java -version`

## ☕ Configurando ambiente JAVA_HOME:

1. Verificar o caminho da instalação do Java:

`sudo update-alternatives --config java`

2. Copie o caminho que aparecerá no terminal, no meu caso:

`/usr/lib/jvm/java-11-openjdk-amd64/bin/java`

3. Vamos editar o arquivo .bashrc:

`sudo gedit ~/.bashrc`

4. Copie o código abaixo e cole no final do arquivo .bashrc. 

*IMPORTANTE: cuidado para não alterar nada no arquivo além de apenas colar no final do mesmo o que vou te disponibilizar a seguir.*

*JAVA_HOME = aqui você coloca o caminho do tópico 4.2, tirando o /bin/java*

`JAVA_HOME=/usr/lib/jvm/java-11-openjdk-amd64
export JAVA_HOME
export PATH=$PATH:$JAVA_HOME`

4.3. Salve o arquivo

4.4. Vamos conferir se a alteração ficou salva:

`cat ~/.bashrc`

5. Feche o terminal e abra novamente

6. Vamos conferir mais uma vez se o Java está instalado na nossa máquina

`java --version`

<p align="right"><em>Créditos: <a href="https://www.youtube.com/watch?v=jARiy3DZdwg">DevSuperior</a></em></p>
  
