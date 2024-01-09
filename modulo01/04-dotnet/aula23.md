<div align="center">
<a href="https://github.com/monicaquintal" target="_blank"><img align="left" height="100" src="../../assets/logo.png" /></a>
<h1>Módulo 01: Fundamentos do C#</h1>
<h2>.NET</h2>
<h3>Aula 23: Tipos de projeto.</h3>
</div>

<div align="justify">

## 1. Definições
- há vários tipos de projeto, entre eles:

### a) Class Library:
- o resultado final é uma DLL.
- não possui interface.

### b) Console Application:
- o resultado final éuma aplicação que roda no terminal.
- pode receber dados, esperar input do usuário.

### c) Projeto Web:
- ASP.NET Web.
- ASP.NET MVC.
- ASP.NET WebAPI.

### d) Projeto Testes:
- Microsoft Tests.

## 2. dotnet cli:
- dotnet new console - Novo Console Application.
- dotnet new classlib - Nova Class Library.
- dotnet new web - Novo projeto ASP.NET Core.
- dotnet new mvc - Novo projeto ASP.NET Core.
- dotnet new webapi - Novo projeto ASP.NET Core.
- dotnet new mstest - Novo projeto Microsoft Test.

## 3. Importante:
- criar um projeto é o mesmo que gerar arquivos iniciais de uma aplicação.
- vai sempre gerar os arquivos na pasta inicial.
- para especificar a pasta, podemos usar o `-o`.
  - `dotnet new console -o MeuApp`.
  - vai criar uma nova pasta chamada MeuApp, com os arquivos dentro. 

## 4. Exemplo:

~~~
mkdir TesteAula23
cd .\TesteAula23\
dotnet new console
// OU dotnet new console -o NovoTeste
~~~

---

[Voltar ao início!](https://github.com/monicaquintal/estudandoC-)