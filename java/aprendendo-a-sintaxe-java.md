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
