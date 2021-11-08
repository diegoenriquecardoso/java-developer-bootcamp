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
  
  ▫️ **public**: qualquer classe de qualquer pacote poderá acessar o atributo ou método.
  
  ▫️ **protected**: qualquer classe definida no mesmo pacote ou subclasse.
  
  ▫️ **sem modificador**: apenas classes definidas no mesmo pacote.
  
  ▫️ **private**: apenas a própria classe.

  ## Métodos 💻
  *Métodos são funções que definem o comportamento de uma classe.*
  
  Tipos de métodos:
  
  ▫️ **Métodos construtores**: definem como uma classe será instansciada (construída).
  ▫️ **Métodos comum**: definem comportamentos que podem ou não estar atribuídos às regras de negócio. Ex.: calcular taxas de um pedido, etc.

  ## Estrutura de condição 💻
  *Estrutura de condição é responsável por fazer o desvio do fluxo de execução do código de acordo com uma dada condição.*
  
  Tipos de estrutura de condição:
  
  ### ▫️ **IF ELSE**:

  ![image](https://user-images.githubusercontent.com/81873935/140590150-fdb4367f-acff-41fb-911a-aa685a84acd3.png)

  ### ▫️ **SWITCH - CASE**:
  
  ![image](https://user-images.githubusercontent.com/81873935/140590114-6222e64b-5570-4834-910d-948aabcca566.png)

  ## Estrutura de repetição 💻
  *Estrutura de repetição é responsável por executar repetidamente uma instrução ou um bloco de instruções até que uma condição esteja sendo feita.*
  
  Tipos de estrutura de repetição:
  
  ### ▫️ while:
  
  ![image](https://user-images.githubusercontent.com/81873935/140590374-1b65c9f1-f283-412a-90cf-19b593922b3a.png)

  ### ▫️ do - while
  
  ![image](https://user-images.githubusercontent.com/81873935/140590539-20075ed4-b006-4d91-b951-0bb2e4091bac.png)
  
  ### ▫️ for
  
  ![image](https://user-images.githubusercontent.com/81873935/140590630-adb663c0-9396-4932-9339-237ae41ae2f9.png)

  ### ▫️ enhanced for

  ![image](https://user-images.githubusercontent.com/81873935/140590744-62dbe101-16ff-4972-86aa-ef61d3632adb.png)

  ## Documentação Java 💻
  
  ▫️ comentários em linha: são feitos com duas barras "//"
  
  ▫️ comentário em bloco: são feitos por uma barra e dois asteriscos "/**" e finalizados por um asterisco e uma barra "*/"

  ## Javadoc 💻
  
  **O que é Javadoc?**
  
  Javadoc é uma ferramenta para documentação no formato HTML que se baseia nos comentários do código-fonte.
  
  Os comentários precisam conter tags para que a documentação fique legível.

  ## Tags Javadoc 💻
  
  ▫️ @author - especifica o autor da classe ou do método
  
  ▫️ @deprecated - identifica classes ou métodos obsoletos
  
  ▫️ @link - possibilita a definição de um link para outro documento local ou remoto através de um URL
  
  ▫️ @param - descreve um parâmetro que será passado a um método
  
  ▫️ @return - descreve qual o tipo de retorno de um método
  
  ▫️ @see - associa a outras classes ou métodos
  
  ▫️ @since - descreve desde quando uma classe ou métodos foram adicionados
  
  ▫️ @throws - descreve os tipos de exceções que podem ser lançadas por um método
  
  ▫️ @version - descreve a versão da classe ou método
  
  ## Comunidades Java 💻
  
  ▫️ OpenSanca - opensanca.com.br
  
  ▫️ SouJava - soujava.org.br
  
  ▫️ DevOpsPBS - devopspbs.org

  ## Requisitos do profissional 💻
  
  Exemplos de Hard Skills:
  
  ▫️ Spring Boot
  
  ▫️ Spring Cloud 
  
  ▫️ Apache Kafka
  
  ▫️ RabbitMQ
  
  ▫️ Arquitetura Cloud

  ## Recursos presentes no Java 11
  
  ▫️ Default methods
  
  ![image](https://user-images.githubusercontent.com/81873935/140741087-aefbf80f-9cc5-4eb5-b2ef-2fc47e68ed85.png)
  
  ▫️ Lambdas
  
  ![image](https://user-images.githubusercontent.com/81873935/140741156-8e25d816-6175-4933-8799-ec9318d88c75.png)
  
  ▫️ Method references
  
  ![image](https://user-images.githubusercontent.com/81873935/140741211-769c2dbb-3257-4f78-9a30-5b5b36c6f2ec.png)
  
  ▫️ Streams
  
  ![image](https://user-images.githubusercontent.com/81873935/140741259-fc1438c9-ec65-4519-87eb-54d6a1604d6a.png)

  ▫️ Datas

  ![image](https://user-images.githubusercontent.com/81873935/140741288-f6bda696-44fd-499f-bc70-6b3fe7f37dfd.png)

  ▫️ Manipulação de Strings 
  
  ![image](https://user-images.githubusercontent.com/81873935/140741884-8f137cd6-8334-42e3-b01b-831266d7c94d.png)

  ▫️ Variavéis por inferência
  
  ![image](https://user-images.githubusercontent.com/81873935/140742075-dbfa5f98-5e95-4709-9b56-a70c6c003de4.png)

  ▫️ Manipulação de arquivos
  
  ![image](https://user-images.githubusercontent.com/81873935/140742467-3f22488c-1df7-4208-8cfd-e9f6bb17cc8b.png)
