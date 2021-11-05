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

5. Dentro da pasta `src` criamos uma pasta chamada `pacote1`

![image](https://user-images.githubusercontent.com/81873935/140567667-37307ba7-535c-4118-8740-20a98bcc25f7.png)

![image](https://user-images.githubusercontent.com/81873935/140567753-0467067a-540b-4f0a-9933-dd382cffbb3c.png)

5. Dentro da pasta `pacote1` criamos um arquivo chamado `PrimeiroPrograma.java` (é importante que a primeira letra das palavras seja maiúsculas.
  
![image](https://user-images.githubusercontent.com/81873935/140567843-82f0c472-135b-4623-94ad-c341a0ca8342.png)

O VSCODE irá gerar automaticamente um package com uma public class para nós.
  
  ![image](https://user-images.githubusercontent.com/81873935/140567912-10875294-c0c4-4092-a2b9-d7baeeda9f7e.png)

6. Dentro do public class, iremos escrever *pu* e selecionar a opção public static void main
  
  ![image](https://user-images.githubusercontent.com/81873935/140568266-4ccffa2a-24cf-4d29-837c-cfe7ff5ac67d.png)

O VSCODE irá gerar automaticamente uma public static void name, onde substituiremos o name por *main*
  
7. Dentro da public static void main, iremos escrever *sysou* e selecionar a opção sysout
  
  ![image](https://user-images.githubusercontent.com/81873935/140568577-da795086-45c3-4ec4-88f3-3b90ffe2f473.png)

8. Temos então, o nosso primeiro Programa em Java, imprimindo 'Hello World!"
  
![image](https://user-images.githubusercontent.com/81873935/140569274-522f1e0b-faf9-447c-81f0-e10247f90c7a.png)


*código para cópia:*
```
package pacote1;
  
public class PrimeiroPrograma {

    public static void main(String[] args) {
        System.out.println("´Hello World!");
    }
}
```

## Palavras reservadas 💻
  Não podemos usar as seguintes palavras para a definição de um nome, de um método, classe ou atributo.
  
![image](https://user-images.githubusercontent.com/81873935/140569641-94671bad-0797-4ca8-980c-8ada2ec5a352.png)

## Declaração de classes 💻

Estrutura básica de uma classe:
  
![image](https://user-images.githubusercontent.com/81873935/140570419-381bacbc-33fb-40a8-b1fe-47d54393c9b6.png)
  
Estrutura com atributos e métodos:
  
![image](https://user-images.githubusercontent.com/81873935/140570499-69754726-e7f0-4b25-b102-6e42c19ef15e.png)
  
Estrutura completa de uma classe:

  ![image](https://user-images.githubusercontent.com/81873935/140570592-3be091f0-3085-40e6-8183-d0e85d61ac60.png)
  
## Modificadores de acesso 💻
  Tipos de modificadores:
  
  ▫️ *public*: qualquer classe de qualquer pacote poderá acessar o atributo ou método.
  
  ▫️ *protected*: qualquer classe definida no mesmo pacote ou subclasse.
  
  ▫️ *sem modificador*: apenas classes definidas no mesmo pacote.
  
  ▫️ *private*: apenas a própria classe.
