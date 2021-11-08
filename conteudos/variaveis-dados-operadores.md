# <p align="center"> ☕ Variáveis, Tipos de Dados e Operadores Aritméticos ☕

  ## Conceituação de Variáveis 💻
  
  > "Um espaço na memória do computador, onde se pode guardar valores."
  
  ### Tipos:
  
  ▫️ Instância: objeto
  
  ▫️ Classe: classe
  
  ▫️ Local: dentro de métodos
  
  ▫️ Parâmetro: na assinatura do método
  
  ## Criação 💻
  
  ### Padrão de definição
  
  `<?visibilidade?><?modificador?> tipo nome <?=valorInicial?>;`
  
  **V**isibilidade: "public", "protected" e "private"
  
  **M**odificador: "static" e "final"
  
  **T**ipo: tipo de dado
  
  **N**ome: nome que é fornecido a variável
  
  **V**alor **I**nicial: valor inicial, caso deseja
  
  ### Convenções e regras:
  
  ▫️ Não devem começar com números;
  
  ▫️ Embora permitido, "$" e "_" devem ser evitados;
  
  ▫️ São case-sensitive;
  
  ▫️ Sem espaços;
  
  ▫️ Não pode ser palavras reservadas do Java.
  
  ### Boas práticas
  
  ▫️ Sempre começar com letra minúscula;
  
  ▫️ Nomes expressivos;
  
  ▫️ Notação camelo (isento variavel final);
  
  ▫️ Quando constante(final) maiúscula e separada por "_".
  
  ## Conceituação de Tipo de Dados 💻
    
  > "São os valores e consequentemente operações que as variáveis podem assumir e sofrer, respectivamente"
    
  ### Tipificação:
    
  ▫️ Estática (forte) **vs** Dinâmica (fraco)
    
  ▫️ Primitivo **vs** Composto

  ### Opções de tipos e Utilização:
  
  ▫️ Textual:
  
  char: caracteres de 16-bit unicode -> `char c = '\u0084';` ou `char c = 'T';`
  
  string: um tipo "especial" -> String s = "T";
  
  ▫️ Numeral:
  
  byte: -128 até 127 -> `byte b = 15;`
  
  byte: -32.768 até 32.767 -> `short s = 15785;`
  
  byte: -2.147.483.648 até 2.147.483.647 -> `int i = 8515785;`
  
  long: -9.223.372.036.854.775.808 até 9.223.372.036.854.775.807 -> `long l = 5938515785L;`
  
  long: +-3.40282347E+38F -> `float f = 3.14... (f);`
  
  double: +-1.79769313486231570E+308 -> `double d = 3.14... (d);`
  
  ▫️ Lógico:
  
  boolean: `true` e `false` -> `boolean s = false`
  
  ▫️ Objeto:
  
  | Tipo de Dado | Valor default |
  | --- | --- | 
  | byte | 0 |
  | short | 0 |
  | int | 0 |
  | long | 0L |
  | float | 0.0f |
  | double | | 0.0d |
  | char | '\u0000' |
  | String (e objetos) | null |
  | boolean | false |
  
  
  ## Operadores Aritméticos 💻
  
  > "São símbolos especiais que são capazes de realizar ações específicas em um, dois ou mais operandos e em seguida retornar um resultado!
  
  ### Tipos:
  
  ▫️ pós-fixado: exp++ ou exp--
  
  ▫️ prefixado: ++exp ou --exp
  
  ▫️ aritmético: +, -, *, / e %
  
  ▫️ atribuição: =, +=, -=, *=, /=, %=
  
  ### Utilização:
  
  | Operador | Precedência |
  | --- | --- |
  | pós-fixado | exp++, exp-- |
  | pré-fixado | ++exp, --exp |
  | multiplicativo | *, /, % |
  | aditivo | +, - |
  | atribuição | =, +=, -=, *=, /=, %= |
  
  ## Conversões (casting) 💻
  
  > "É a transformação de uma determinada variável de tipo menos específico para um tipo mais específico ou vice-versa"
  
  ### Tipos:
  
  ▫️ Upcast (implícito): promoção para um dado maior, não há preocupação para dizer onde está indo
  
  ▫️ Downcast (explícito): uma variavel de tipo de dado maior e é rebaixada a menor 
  
  ### Utilização:
  
  | | byte | short | char | int | long | float | double |
  | --- | --- | --- | --- | --- | --- | --- | --- |
  | byte | | U - I | char | U - I | U - I | U - I | U - I |
  | short | D - E |  | char | U - I | U - I | U - I | U - I |
  | char | D - E | D - E |  | U - I | U - I | U - I | U - I |
  | int | D - E | D - E | D - E |  | U - I | U - I | U - I |
  | long | D - E | D - E | D - E | D - E | | U - I | U - I |
  | float | D - E | D - E | D - E | D - E | D - E | | U - I |
  | double | D - E | D - E | D - E | D - E | D - E | D - E | |
  
  U - I: UPCAST IMPLÍCITO  |  D - E: DOWNCAST EXPLÍCITO
  
    [<p align="center"> ⬅️ Conteúdo anterior](https://github.com/vitoriadevalois/java-developer-bootcamp/blob/main/conteudos/ecossistemajava.md) | [Próximo conteúdo ➡️](https://github.com/vitoriadevalois/java-developer-bootcamp/blob/main/conteudos/logica-condicional-fluxos.md)
