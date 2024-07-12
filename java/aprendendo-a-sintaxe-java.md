Anotações feitas para estudo do curso "Aprendendo a Sintaxe Java" criado pela DIO e disponbilizado no bootcamp do Santander com a DIO

# Introdução

### Objetivo do curso

Apresentar as regras essenciais para a construção de códigos com base na linguagem Java.

### Pré-requisitos

- JDK instalado
- IDE escolhida
- Diretório do projeto definido

## Anatomia da Classe

### Assuntos

- Estrutura inicial
- Padrão de nomenclatura
- Declarando variáveis e métodos
- Identação
- Organizando arquivos
- Java Beans

_Para Saber mais: [Java Básico](https://glysns.gitbook.io/java-basico/)_

---

# Anatomia das Classes

A escrita de códigos de um programa é feito através da composição de palavras pré-definidas pela linguagem com as expressões que utilizamos para determinar o nome do nossos arquivos, classes, atributos e métodos.

É muito comum mesclarmos expressões no idioma amricano com o nosso vocabulário. Existem projetos que recomendamos que toda a implementação do seu programa seja escrita na língua inglesa.

## Sintaxe de declaração de uma nova classe:

```Java
public class MinhaClass {
    // Seu código aqui
}
```

### O que escrever na minha classe criada?

Se a minha classe é uma classe _executável_, se ela é uma classe que tem a capacidade de realizar uma inicialização do projeto de forma independente, essa classe precisa ter o método especial, principal, o método **main**.

- Ele terá uma característica única na sua representação de inicialização.

#### Padrão main

```java
public class MinhaClasse {
    public static void main (String [] args)

        System.out.print ("Olá turma, sejam bem-vindos");
}
```

### Recomendações para declarar uma variável

Para declarar uma variável nós podemos utilizar caracteres, números e símbolos, porém devemos seguir algumas regras da linguagem.

- Deve conter apenas letras, _ (underline), $ ou os números de 0 a 9;
- Deve obrigadamentoriamente se iniciar por uma letra (preferêncialmente), _ ou $, jamais com número;
- Deve iniciar com uma letra minúscula (boa prática);
- Não deve conter espaços;
- Não podemos usar palavras-chave de linguagem;
- O nome deve ser o único dentro de um escolpo.

```java
// Declaração de variáveis *inválidas*

int numero&um = 1; // Os únicos símbolos permitidos são _ e $
int 1numero = 1; // Uma variável não pode começar com números
int numero um = 1; // Não pode ter espaço no nome da variável
int long = 1 // long faz parte de palavras reservadas da linguagem

// Declaração de variáveis *válidas*

int numero$um = 1;
int numero1 = 1;
int numeroum = 1;
int longo = 1;
```

### Declarando variáveis e métodos
```Java
// Estrutura

Tipo NomeBemDefinido = Atribuição (opcional em alguns casos)

// Exemplo

int idade = 23;
double altura = 1.62;
Dog spike; // observe que aqui a variável spike não tem valor
```

- Declarando métodos em Java segue em uma estrutra bem simples:

```Java
// Estrutura

TipoRetorno NomeObjetivoNoInfinitivo Parametro(s)

// Exemplo

int somar (int numeroUm, int numero2);

String formatarCep (long cep);
```
### Identação
É um termo utilizado para escrever o código do programa de forma hierárquica, facilitando assim a visualização e entendimento do programa.

### Organizando arquivos
À medida que nosso sistema vai evoluindo, surgem novos arquivos (código fonte) em nossa estrutura de arquivos do projeto. Isso exige que seja realizado uma organização destes arquivos através de pacotes (packages).

### Java Beans
Umas das maiores dificuldades na programação é escrever algoritmos legíveis a níveis que sejam compfeendidos por todo seu time ou por você mesmo no futuro. Para isso a linguagem Java sugere, através de convenções, formas de escrita universal para nossas classes, atributos, métodos e pacotes.
Mais cedo já aprendemos alguams regras de declaração de variáveis, mas agora iremos conhecer algumas sugestões de nomenclatura:
- Uma variável deve ser clara, sem abreviações ou definições sem sentido;
- Uma variável é sempre no singular, **exceto quando se referir a um array ou coleção**
- Defina um idioma único para sua variável. Se você for declarar variáveis em inglês, defina todas em inglês.

#### Não recomendado
```Java
double salMedio = 1500.23 // variável abreviada
String emails = "aluno@escola.com" // confuso se o valor está em plural e só tem um e-mail definido
String myName = "Joseph" // Se o idioma for pt-BR, o valor deve estar em pt-BR
```

#### Recomendado
```Java
double salarioMedio = 1500.23;
String email = "aluno@escola.com";
String [] emails = {"aluno@escola.com","professor@escola.com"} // dois ou mais e-mails
String meuNome = "Joseph";
```


### Métodos
Os métodos deverão ser nomeados como verbos, através de uma mistura de letras minúsculas e maiúsculas. Em princípio todas as letras que compõem o nome devem ser mantidas em minúsculo, com exceção da primeira letra de cada palavra composta, a partir da segunda palavra.
```Java
somar(int n1, int n2){}
abrirConexao(){}
concluirProcessamento() {}
findById(int id){} // não se assuste, você verá muito método em inglês em sua jornada
calcularImprimir(){} // há algo de errado neste método, ele deveria ter uma única finalidade
```