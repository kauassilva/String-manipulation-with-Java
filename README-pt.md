# Manipulação de Strings em Java
Como manipular String com Java, explorando as principais características da classe String.

Neste repositório, abordarei de forma abrangente a introdução a Strings em Java, operações básicas para manipulação de Strings, modificação de Strings, pesquisa e verificação de Strings, formatação de Strings e expressões regulares. Espero que as informações apresentadas sejam úteis.



## 1. Introdução a Strings em Java


### Compreendendo Strings
As Strings são elementos essenciais na ciência da computação e na programação, sendo amplamente utilizadas para representar sequências de caracteres como letras, números e símbolos. Eles desempenham um papel fundamental no manuseio e processamento de informações em muitas áreas, desde o desenvolvimento de software até a análise de dados e o processamento de linguagem natural.

Como dito anteriormente, uma String é uma sequência de caracateres. Pense em uma String como uma palavra, uma frase ou até mesmo um parágrafo. Ela é delimitada por aspas, o que significa que qualquer texto dentro das aspas é considerado uma String. Por exemplo, "Olá, mundo!", é uma String.

Uma característica das Strings é sua imutabilidade em muitas linguagens de programação. Isso significa que, uma vez que uma String é criada, ela não pode ser alterada. Se você quiser alterar uma String, na verdade você estaria criando uma nova String com as alterações, mas mantendo a original intacta. Por exemplo, se você tem a String "Olá," e deseja adicionar o texto " mundo!", você criaria uma nova String com a concatenação das duas: "Olá, mundo!". Isto é importante, porque garante a integridade dos dados.


### Como criar e inicializar Strings
Em Java, a classe `String` é usada para representar sequências de caracteres. Há várias maneiras de se para criar um objeto `String`, mas por enquanto vamos ver só duas delas.

1. Declaração e inicialização direta - você pode criar uma String atribuindo um valor a uma variável do tipo `String`:

    ``` Java
    String minhaString = "Olá, mundo!";
    ```
    
2. Construtor `String` - Outra forma de criar um objeto `String` é usando o construtor da classe `String`:

    ``` Java
    String minhaString = new String("Olá, mundo!");
    ```
    
 
### Concatenação de Strings
A concatenação de Strings é o processo de combinar/juntar duas ou mais Strings para formar uma única String. É como juntar diferentes pedaços de texto para criar uma nova String. Repare que isso também pode ser usado para criar uma String. Para fazer a concatenação, há duas maneiras principais:

1. Operador (+):

    ``` Java
    String parte1 = "Olá";
    String parte2 = "mundo!";
    String minhaString = parte1 + ", " + parte2;
    ```

3. Método `concat()`:

    ``` Java
    String parte1 = "Olá";
    String parte2 = "mundo!";
    String minhaString = parte1.concat(", ").concat(parte2);
    ```
