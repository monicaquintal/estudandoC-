<div align="center">
<a href="https://github.com/monicaquintal" target="_blank"><img align="left" height="100" src="../../assets/logo.png" /></a>
<h1>Módulo 01: Fundamentos do C#</h1>
<h2>Linguagens e Compiladores</h2>
<h3>Aula 06: Tipagem de dados.</h3>
</div>

<div align="justify">

> C# é uma linguagem de alto nível, compilada e fortemente tipada.

## 1. Introdução

- linguagens fortemente tipadas obrigam a especificar o tipo de dado da informação.
- menor liberdade e maior otimização.
- um tipo de dado define o formato dele, como número, letra, cadeia de caracteres e etc.
- exemplos:

### a) C# (linguagem fortemente tipada):

~~~c#
int idade = 18; // OK
int idade = 18.2; // ERRO
int idade = "18"; // ERRO
int idade = 'a'; // ERRO
~~~

### b) JavaScript (linguagem não tipada):

~~~js
let idade = 18; // OK
let idade = 18.2; // OK
let idade = "18"; // OK
let idade = 'a'; // OK
~~~

## 2. Definições

- fazer a tipagem = definir tipos, é padronizar dados (para nós e para o processador/memória).
- o let, por exemplo, utiliza sempre o mesmo tamanho de alocação da memória, não possuindo uma otimização.
- tipando, temos uma otimização!!!
  - no C#, por exemplo:
    - int: 32 bit.
    - float: 32 bit. 
    - double: 64 bit.
    - decimal: 128 bit.

---

[Voltar ao início!](https://github.com/monicaquintal/estudandoC-)