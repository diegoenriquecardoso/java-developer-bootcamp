# <p align="center"> 💻 Introdução ao Ecossistema Java 💻
[![JAVA](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)](#)

## Requisitos ❗
✔️ Distribuição Linux (Ubuntu, Mint, etc)
  
✔️ Conhecimentos sobre comandos básicos no terminal Linux
  
✔️ Conhecimentos em lógica de programação
  
✔️ Conhecimento básico em linguagem de programação
  
✔️ Conhecimento em Programação Orientada a Objetos
  
## O que é JAVA? ☕
> "Java é uma linguagem de programação e plataforma computacional lançada pela primeira vez pela Sun Microsystems em 1995". **Oracle**, 2021. 
> 
> Disponível em <https://www.java.com/pt-BR/download/help/whatis_java.html>

### Características
▫️ Compilada
  
▫️ Interpretada
  
▫️ Fortemente tipada
  
▫️ Linguagem de alto nível
  
▫ Executada em uma máquina virtual - JVM (Java Virtual Machine)
  
## O que é JVM? ☕
  *"JVM (Java Virtual Machine) é uma máquina virtual responsável pela tradução dos ByteCodes oriundos do compilador Javac (Java Compiler) em código de máquina de cada sistema operacional.*
  
### Características
▫️ Execução de pilhas
  
▫️ Gerenciamento de memória
  
▫️ Gerenciamento de threads
  
▫️ Otimização de código (Compilação JIT - Just In Time)
  
▫️ Garbage Collector (GC)

## Qual a diferença entre JRM e JDK?
▫️ **JRE (Java Runtime Environment)**: responsável por executar os programas em Java.
  
▫️ **JDK (Java Development Kit)**: utiliários que permitem o desenvolvimento de programas em Java. Já possui a JVM para executar os programas.

## Quais os tipos de plataformas Java?
▫️ **Java SE (Java Standard Edition)**: contém as especificações do Java e pode ser implementado por diversas empresas como Oracle, OpenJDK, Azul Zulu, etc.
  
▫️ **Java EE (Java Enterprise Edition)**: contém todas as especificações do Java SE e um número de programas úteis para que executem em servidores. Em 2019 foi nomeado para Jakarta EE.
  
▫️ **Java ME (Java Micro Edition):** contém todas as especificações para desenvolvimento de programas para dispositivos pequenos como celulares, PDAs etc.

## Primeiro Programa Java ☕
Utilizando o VSCODE, podemos seguir os seguintes procedimentos para criar um projeto java:
  
1. No topo do VSCODE, podemos acessar a aba **Ver** e logo em seguida acessar a **Paleta de Comandos**. Você também pode utilizar as teclas de atalho *CTRL + SHIFT + P*.
  
![image](https://user-images.githubusercontent.com/81873935/140566466-6194d17e-59e6-4d5b-89a2-5f396c2a0fba.png)

2. Em seguida digitamos *"java"* e selecionamos a opção **Java: create a java project** para criarmos um projeto java.
  
![image](https://user-images.githubusercontent.com/81873935/140566677-f0191632-a556-45d1-9d4c-8faae21f7554.png)

3. Selecionamos a opção *No build tools*.
  
4. Escolhemos o local onde nosso projeto ficará. (Eu, por exemplo, criei uma pasta workspace dentro dos Documentos do computador, assim posso organizar os meus exercícios dentro dessa pasta).

5. Dentro da pasta `src` criamos um arquivo chamado `PrimeiroPrograma.java` (é importante que a primeira letra das palavras seja maiúsculas.

![image](https://user-images.githubusercontent.com/81873935/140567377-3cf0c5b7-c663-4652-a8c0-3091fd91d317.png)

![image](https://user-images.githubusercontent.com/81873935/140567447-bb24801c-4090-4602-8d0a-ead47862ce21.png)

6. Vamos escrever o seguinte código:

```
package com.dio;
  
public class PrimeiroPrograma {

    public static void main(String[] args) {
        System.out.println("´Hello World!");
    }
}
```
