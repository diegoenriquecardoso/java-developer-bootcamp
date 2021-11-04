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
