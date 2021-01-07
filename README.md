# OO-Logica-CSharp

## O que vamos aprender:
   - C#: linguagem de programação;
   - .NET: Pataforma de desenvolvimento microsoft, que se pode usar linguagens de programação além do C#, composto por:
       - Bibliotecas:
           - BCL - Base Class Library - Biblioteca de classes base;
           - CLR - Common Language Runtime - Máquina Virtual, possui garbage collectior;
       - .NET Framework ( Funcionamento em sistemas Windows);
       - Mono, insere o .NET em multiplataforma, também usado pela Unity;
       - Xamarim utiliza Mono, crossplataform mobile;
       - .NET 5

## Como funciona o C#
   - C# é uma linguagem híbrida, ou seja, ela mescla o funcionamento de uma linguagem intempretada com o de uma linguagem compilada;
   - Passa por uma pre-compilação que gera o Bytecode(linguagem pré-complilada em CIL - Common Intermediate Language);
   - Para que o código seja executado em SO's diferentes é necessário que se tenha o CLR instalado nos respectivos SO's, sem que o código seja necessário ser modificado.
   - ### Projetos:
    - Sua aplicação é composta por um conjunto de classes, agurpadas por um namespace (agrupamento lógico);
    - Porém em projetos maiores existe o Assembly - DLL ou EXE (agrupamento físio) de outros namespaces, representado cada um uma parte de um sistema;
    - E por fim a Aplicação completa (Solution), é composta pelo conjunto de assemblies;

## Ferramentas:
   - O curso original opita por utilizar o Visual Studio Community 2019, que ao instaçar já vem com as configurações, porém eu optei por utilizar o visual studio code, que é mais simples e mais leve, porém teremos de instalar o SDK a parte;
   - Visual Studio Code: https://code.visualstudio.com/download;
   - SDK 3.1.3: https://dotnet.microsoft.com/download/dotnet-core/3.1

## Fonte:
   - Esse repositório é baseado no curso da udemy :https://www.udemy.com/course/programacao-orientada-a-objetos-csharp, porém com atualizações e mudanças minhas.
