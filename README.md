# Linguagem de programação Java
Revisão sobre a linguagem Java

## Tópicos de Estudos

* [Linguagem de programação Java](01.md)
  * Paradigmas de Programação
  * Modelo de Tipagem de dados
  * Modelo de construção da Linguagem  
  * Estilo de código
  * Versões
    * Java 1.8
      * Novas funcionalidades 
    * Java 11
      * Novas funcionalidades
    * Java 18
      * Novas funcionalidades
    * Java 19 
      * Novas funcionalidades
  * Conjunto de palavras reservadas
  * Ambiente de Desenvolvimento e Ferramentas
    * Documentação oficial
    * JDK
    * IDEs
      * Como criar um projeto Java em uma IDE
  * Mercado
    * Popularidade 
      * Tiobe
      * Survey da Stackoverflow 
      * Survey da Jetbrains 
    * Vagas e salários 
      * Survey da Stackoverflow 
      * Survey da Jetbrains  
    * Áreas de aplicações da linguagem Java 
      * Survey da Stackoverflow 
      * Survey da Jetbrains  
    * Principais bibliotecas/frameworks 
      * Survey da Stackoverflow 
      * Survey da Jetbrains  
* [Hello World](02.md)
  * Estrutura mínima de um código Java
  * Nome do arquivo e Extensão
  * Nome da classe
  * Método main
  * Escrever dados no console
  * Indentação de código
  * Delimitação de uma instrução
  * Delimitação de bloco de instruções
  * Compilação e Execução via linha de comando
* [Tipos de Dados e operadores](03.md)
  * Tipos de Dados
      Os tipos primitivos são boolean, byte, char, short, int, long, float e double
  * Declarações de variáveis
      As variaveis sao feitas geralmente no inicio do programa, exemplo:
      String carroModelo 1.

  * Nomes válidos para variáveis e boas práticas 
      São nomes simples e diretos, sempre deve ser utilizado o métudo camelcaze, Exemplo
      String exemploDeVariavel;
  * Atribuição de valores
      Acontece quando é definido o valor de uma variavel, exemplo:
      Int anoDeLançamento = 1990;

  * Operadores
    * Operadores aritméticos
        Os principais são:
          Soma +
          Subtração -
          Divisão /
          Multiplicação *

    * Operadores booleanos
        True ou False, Exemplos:
          boolean carroComProblema = true;

  * Conversão de tipos de dados
      É possivel pasar usando o comando "To(tipo de dado desejado) exmplo:"
        *ToDecimal
        *ToString
        *ToBoolean
        *ToChar
* [Saída de Dados](04.md)
  * Método System.out.println
      System.out.println é utilizado para exibir informações na tela, e pular uma linha em sequência
  * Método System.out.print
       System.out.println é utilizado para exibir informações na tela, e não pular uma linha em sequência
  * Exibir o valor de uma variável
      String modeloDeCarro = "Celta"
      System.out.println(modeloDeCarro)
  * Exibir o valor de um decimal  
      double numeroDecimal = 10.00
      System.out.println(numeroDecimal)
* Classe Math
  * Definição
      Classe que permite realizar operações de matematica expecificas.
  * Principais operações 
      math.randon
      Math.Abs
* String
  * Concatenação de String
    String modeloCarro1 = "Celta";
    System.out.println("Eu tenho um " + modeloCarro1 + " Turbo");

  * Principais operações sobre String
    -Concatenações e atribuições

  * Comparação de String 
    "macaco" == "leao"
  * Diferença entre String e caracter
    String é um conjunto de palavras, um char é apenas uma letra.
* Entrada de Dados
  * Classe Scanner
    * Obter um valor inteiro
        Scanner sc1 = new Scanner(System.in);
        int valorInteiro = 1990;
    * Obter um valor decimal
        Scanner sc1 = new Scanner(System.in);
        float valorDecimal = 19.209;
    * Obter um valor de texto 
        Scanner sc1 = new Scanner(System.in);
        String textoString = "Maria Silva";
* Fluxo de Controle
  * Estruturas de Decisões
    * if-else-then
        Utilizado para realizer validações, exemplo:
          int numeroUm = 10;
          int numeroDois = 90;
          if (numeroDois > numeroUm){
            system.out.println("Entrou na validação");
          }
    * switch
        Utilizado para validar o que fazer com um resultado recebido, exemplo:
        int valor = 10;
          switch(valor){
            case 4:
              System.out.println("Não vai entrar aqui");
              [breake;]
            case 7:
              System.out.println("Não vai entrar aqui");
              [breake;]
            case 10:
              System.out.println("Vai entrar aqui");
              [breake;]
          }
  * Estruturas de Repetições
    * for
        Utilizado para fazer repetiçoes, exemplo:
          for(int i = 100;i < 100; i++){
            System.out.println("Vai repetir ate i for maior que 100");
          }

    * while
        Utilizado para fazer repetições tambem, exemplo:
          Int valor = 10;
            while(valor < 100){
              System.out.println("Vai repetir ate i for maior que 100");
              i++;
            }

    * do-while 
        Utilizado para fazer repetições tambem, exemplo:
          Int valor = 10;
          do{
            System.out.println("Vai repetir ate i for maior que 100");
              i++;
          }while(valor < 100);

    * Comandos break e continue
        Utilizado para controlar o fluxo do seu programa.
          int valorUm = 100;
          int valorDois = 200;

          if(valorUm > valorDois){
            break
          }
* Arranjos e Matrizes
  * Definição matemática
    Um array ou matrizes são estruturas de dados que contém uma série de dados ordenados, chamados "elementos"
  * Declaração de arranjos
      int[] a = new int[4];
  * Declaração de matrizes
      int [][]matriz = new int[][] { {0, 0, 0}, {0, 0, 0}, {0, 0, 0} };
  * Percorrer arranjos
      ArrayList lista = new ArrayList();
        String[] array = {"true", "true", "true", "false", "false"};
        for(int x = 0; x < array.length; x++){
            if(array[x].equals("true")){
                lista.add(x);
            }
        }
  * Percorrer matrizes
      for ( i=0; i<3; i++ )
  for ( j=0; j<3; j++ )
  {
     scanf ("%d", &matriz[ i ][ j ]);
  }
    * Linha a linha
      import numpy as np 
  
        array = [[1, 13, 6], [9, 4, 7], [19, 16, 2]] 
        arr = np.array(array) 
          
        print('printing array as it is') 
        print(arr) 
          
        print('printing 0th row') 
        print(arr[0, :]) 
          
        print('printing 2nd column') 
        print(arr[:, 2]) 
        print('selecting 0th and 1st row simultaneously') 
        print(arr[:,[0,1]])
    * Coluna a coluna
        import numpy as np 
          array = [[1, 13, 6], [9, 4, 7], [19, 16, 2]] 
          arr = np.array(array) 
            
          print('printing array as it is') 
          print(arr) 
            
          print('selecting 0th column') 
          print(arr[..., 0]) 
            
          print('selecting 1st row') 
          print(arr[1, ...]) 
    * Em diagonal 
        int i, j, m[][] = new int[N][N];

        // Ler matriz   
        for (i=0; i<N; i++) {
          //informa linha
          System.out.printf("Informe os elementos %da. linha:\n", (i+1));
              for (j=0; j<N; j++) {
                //informa qual numero deve se colocar
                System.out.printf("m[%d][%d] = ", i, j);
                m[i][j] = ler.nextInt();
              }
          // salta linha para n ficar confuso
          System.out.printf("\n");
  * Utilizar arranjos e matrizes como parâmetros de métodos 
      public class Main{
          public static void main(String[] args)
          {
            int[] arr; //Declaration
      arr = new int[5]; //Creation
      //Initialization
      arr[0] = 1;
      arr[1] = 3;
      arr[2] = 5;
      arr[3] = 7;
      arr[4] = 9;
      //Accessing Array Elements
      System.out.println("Second Element: " + arr[1]);
      System.out.println("Fourth Element: " + arr[3]);
      }
      }
* Tratamento de Exceções
  * Definição
  * Exceções comuns
    * Divisão por zero
    * Conversão de tipos de dados inválidos
    * Acessar uma posição inválida em um arranjo
    * Acessar uma String nula
  * Bloco para capturar uma exceção 
  * Bloco para capturar diferentes exceções 
  * Bloco finally
  * Lançar uma exceção
* Métodos estáticos
  * Estrutura de declaração de um método estático
  * Nomes válidos e boas práticas 
  * Parâmetros 
  * Retorno
  * Utilização de métodos estáticos 
    * Disponíveis na mesma classe
    * Disponíveis em outra classe/arquivo. 
  * Recursão 
* Classe
  * Definição
    * Representação de classe e objeto na UML
    * Diferença entre classe e objeto
  * Atributos
  * Métodos
  * Construtor 
  * Objeto
  * Inicialização de um objeto 
  * Utilização de um objeto
  * Comparação de objetos
  * Método toString
  * Visibilidade de atributos e métodos
    * Público
    * Privado 
  * Sobrecarga de métodos
  * Sobrecarga de construtores
* Pacotes 
  * Definição
     * Representação de pacotes na UML
  * Definição de um pacote em uma classe
  * Importando uma classe de um pacote diferente
  * Visibilidade de classes, atributos e métodos
     * Default/Pacote  
  * Pacote default
    * Importar uma classe em um pacote default 
* Escopo de classe e objeto
  * Definição 
  * Palavra reservada static 
* Herança
  * Definição
     * Representação de herança na UML
  * Criação de uma classe que realiza herança 
  * Sobreescrita de métodos
  * Polimorfismo
    * Conversão de tipos 
  * Visibilidade de atributos e métodos
     * Protegido
  * Palavra reservada super 
     * Encadeamento de construtor 
     * Encadeamento de método
* Interface
  * Definição
     * Representação de interface na UML
  * Criação de uma classe que implementa uma interface
  * Sobreescrita de métodos
  * Polimorfismo
    * Conversão de tipos 
* Classe abstrada
  * Definição
     * Representação de classe abstrata na UML
  * Criação de uma classe que extende uma classe abstrata
  * Polimorfismo
    * Conversão de tipos 
* Coleções 
  * Definição
  * List e Arraylist 
    * Aplicações
    * Declaração
    * Utilização
      * Adicionar elementos
      * Acessar elementos
      * Atualizar elementos 
      * Remover elementos 
  * Map e HashMap
    * Aplicações 
    * Declaração
    * Utilização
      * Adicionar elementos
      * Acessar elementos
      * Atualizar elementos 
      * Remover elementos 
* Tipo Enumerado
  *  Definição
     * Representação de tipos enumerados na UML
* Representação de tempo
  * Classe Date
  * Classe Calendar
  * API Date/Time Java 8
    * LocalDate
    * LocalTime
    * LocalDateTime
    * Period
    * Duration
    * Formação de Date/Time 
* Modificador final
  * Definição
    * Representação de final no diagrama UML 
  * Modificador final em uma variável
    * Variável  de tipo primitivo
    * Objeto 
  * Modificador final em um atributo
    * Atributo primitivo
    * Objeto 
  * Modificador final em um método
  * Modificador final em uma classe
* Objeto imutável
  * Definição
  * Aplicações
  * Como criar um objeto imutável
  * Como modificar um objeto imutável 
* Tipos Genéricos
  * Definição
     * Representação de tipos genéricos na UML
  * Criação de classes com tipos genéricos
  * Inicialização de objetos com tipos genéricos  
* Testes Unitários
  * TDD
  * JUnit
    * Adicionar JUnit no projeto Java
  * Teste assertEquals
  * Teste assertTrue/assertFalse
  * Teste assertNull/assertNull
  * Teste assertArrayEquals  
  * Teste fail
  * Teste capturar uma exception
* JDBC
  * Definição
  * Driver de conexão 
  * Como adicionar o driver de conexão no projeto Java
  * Criação de uma conexão com o banco de dados
    * Classe DataManager
    * String de conexão
      * Banco SQLite
      * Banco MySql
      * Banco Postgre 
    * Classe Connection
  * Enviar instruções SQL
    * Classe Statement
    * Classe PreparedStatment   
  * Consultar registros no banco de dados
    * Classe ResultSet
    * Obter um registro
    * Obter uma coleção de registros
  * Bloco de instruções try-with-resources
  * Captura de exceções
    * Driver não encontrado
    * Conexão inválida
    * Tabela não encontrada
    * Registro não encontrado
    * Erro ao inserir/atualizar
    * Erro ao consultar
  * Design Patterns
    * Singleton Factory para criação de conexões   
      * Representação na UML
    * DAO para manipular dados de uma tabela   
      * Representação na UML

## Listas de Exercícios

[SCHEIBEL, Glaucio. Exercícios de Programação](https://github.com/glaucioscheibel/exercicios)

[Beecrowd](https://www.beecrowd.com.br/judge/pt/)

[Leetcode](https://leetcode.com)

[HackerRank](https://www.hackerrank.com)

[Exercism](https://exercism.org/tracks/java)



## Referências Bibliográficas

FURGERI, SÉRGIO. Java 8 Ensino Didático: Desenvolvimento e Implementação de Aplicações. Saraiva Educação SA, 2018.

Schildt, Herbert. Java para iniciantes. Bookman Editora, 2015.

Finegan, Edward, and Robert Liguori. OCA Java SE 8: Guia de Estudos para o Exame 1Z0-808. Bookman Editora, 2018.

Bloch, Joshua. Java Efetivo: 3a edição. Alta Books Editora, 2019.

Martin, Robert C. Código limpo: habilidades práticas do Agile software. Alta Books, 2019.

Fowler, Martin. UML Essencial: um breve guia para linguagem padrão. Bookman editora, 2014.
