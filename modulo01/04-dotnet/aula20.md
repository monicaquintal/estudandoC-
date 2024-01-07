<div align="center">
<a href="https://github.com/monicaquintal" target="_blank"><img align="left" height="100" src="../../assets/logo.png" /></a>
<h1>Módulo 01: Fundamentos do C#</h1>
<h2>.NET</h2>
<h3>Aula 20: Instalação.</h3>
</div>

<div align="justify">

## 1. Em resumo:

### a) Runtime e SDK:
- para fazer uso dos recursos do .NET, primeiro realizar a instalação, que se divide em duas: `SDK` e `Runtime`.
  - ***Runtime*** é o responsável por executar e gerenciar as aplicações.
  - ***SDK*** (Software Development Kit) será o responsável por nos auxiliar no desenvolvimento delas.
- em resumo, se você já tem uma aplicação criada (EXE ou DLL) e quer apenas executar esta aplicação, você não precisa instalar o SDK, apenas o Runtime.
  - exemplo: máquinas onde nossas aplicações irão rodar, como servidores ou a máquina de um cliente. Elas não precisam do SDK instalados para rodar as aplicações, apenas do Runtime.
- o pacote do SDK é maior, pois contém tudo que precisamos para desenvolver nossas aplicações, enquanto o Runtime contém o mínimo necessário para que elas sejam executadas.

### b) Versões
- as versões do .NET podem coexistir lado-a-lado em sua máquina. 
- ou seja, é possível ter as versões 2.0 e 3.1 instaladas ao mesmo tempo, não precisando remover uma instalação para adicionar uma mais recente.

### c) LTS
- sigla para Long Term Support ou em suporte de longa data.
- significa que a Microsoft continuará a trabalhar nesta versão por um bom tempo.
- a palavra "recomended" em frente ao nome do framework significa que esta é a versão atual recomendada, enquanto a palavra LTS significa que esta versão terá uma longa vida de suporte.

## 2. Instalação:

- sempre busque a [instalação oficial do .NET](https://dotnet.microsoft.com). 
- caso queira ir direto para o download da versão desejada basta adicionar os seguintes parâmetros na URL https://dotnet.microsoft.com/`download`/`dotnet-core`/`$VERSAO`.
  - $VERSAO é a versão do .NET que você deseja baixar, no caso utilizaremos a 3.1. 
  - no caso, nossa URL fica assim https://dotnet.microsoft.com/download/dotnet-core/3.1, e ao acessar este endereço nos será listado tanto o SDK quanto os Runtimes.

### a) Download da SDK
- fazer o download do pacote desejado, que fica na coluna Installers para o seu sistema operacional.
- tanto a instalação no Mac ou Windows são realizadas através de um wizard (Passo a passo). No Linux é necessário a execução de alguns comandos, mas de forma geral são bem simples.

### b) Runtimes
- a instalação do Runtime é dividida em três partes, sendo ASP.NET para aplicações Web, Desktop para aplicações Desktop e .NET Core para demais aplicações que não são necessariamente Web nem Desktop.
- esta divisão permite que os pacotes de execução sejam ainda menores, mais fáceis de distribuir e instalar.
- caso necessário, todos podem ser instalados juntos na mesma máquina, lado a lado como comentado sobre o SDK. O mesmo vale para diferentes versões do Runtime que sejam necessárias.
- para o desenvolvimento de aplicações, tudo que precisamos já está no SDK que instalamos previamente, ou seja, não há a necessidade de instalar um Runtime neste momento.

> Em caso de dúvidas, acessar [aqui](https://balta.io/blog/dotnet-instalacao-configuracao-e-primeiros-passos).

---

[Voltar ao início!](https://github.com/monicaquintal/estudandoC-)