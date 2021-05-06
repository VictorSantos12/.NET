<div align="center">
  <img src="https://user-images.githubusercontent.com/61476935/117233455-8a149a00-adf9-11eb-8fdf-57f6fee37a2c.png" >
</div>
<br>
<img src="https://img.shields.io/static/v1?label=.NET&message=infrastructure&color=purple&style=for-the-badge&logo="/>

 
O .NET é uma infraestrutura de desenvolvimento criada e mantida pela Microsft, cuja criação visa reunir de forma
prática recursos que formam um ambiente de desenvolvimento que abrangesse multiplas linguagens de
programação, ampliando a forma com que se desevolvia aplicações no Windows.
 
<h2>
  Implementações do .NET
</h2>

As aplicações .NET estão presentes em grande parte dos ambientes de desenvolvimento da atualidade. Com os recursos
disponibilizados pela Microsoft é possível criar aplicações para praticamente qualquer plataforma hoje existente. Do
Asp.NET para Web ao ML.NET para o desenvolvimento de I.A's, a infraestrutura .NET tem sido uma das mais importantes
do mercado de T.I das últimas decadas.

Uma aplicação .Net é desenvolvida para e roda em uma das seguintes implementações do .Net:

<ul>
   <li>.Net5 (.Net Core e versões anteriores)</li>

   <li>.Net Framework</li>

   <li>Mono</li>

   <li>Universal Windows Plataform (UWP)</li>
</ul>


<h2>.NET 5</h2>


O .Ne 5 é uma implementação de plataforma crusada do .NET projetada para lidar com cargas de trabalho
de servidores e nuvem em escala, além de aplicações desktop. Sendo multiplataforma, o .NET 5 é compatível
com Windows, macOS, e Linux.  Ele implementa o .NET Standard, de modo que o código que se destina ao .NET
Standard pode ser executado no .NET 5. Sendo alguns exemplos o Asp.NET core, Windows Forms e o Windows
Presentation Foundation (WPF) 


<h2>.NET Framework</h2>

 
O .NET framework foi a primeira versão da plataforma a ser lançada, existindo desde 2002. Sendo um framework,
ou seja, uma série de bibliotecas que possibilitam o desenvolvimento de aplicações de formas distintas com
propósitos variados, sendo estas capazes de serem implementadas de inúmeras formas, porém, restritas ao
ambiente Windows, as libs disponibilizadas pela tecnologia .NET criaram um ambiente de desenvolvimento
bastante prático. Isso devido as facilitações que tais ferramentas traziam para o desenvolvedor,
deixando a cargo dele apenas as especificações do programa a ser criado. O .NET Framework é
otimizado para construir aplicativos de desktop do Windows.


<h2>Mono</h2>


Mono é uma implementação .NET usada principalmente quando um pequeno tempo de execução é necessário. É o
tempo de execução que alimenta os aplicativos Xamarin no Android, macOS, iOS, tvOS e watchOS.. Mono
também alimenta jogos construídos com o motor Unity. Ele oferece suporte a todas as versões do
.NET Standard publicadas atualmente.


<h2>Universal Windows Plataform (UWP)</h2>


UWP é uma implementação do .NET usada no desenvolvimento de aplicações e softwares Windows touch-enabled,
e para a Internet das Coisas (IoT). Ele foi projetado para unificar os diferentes tipos de dispositivos
que suportes, incluindo PCs, tablets, telefones e até mesmo o Xbox. A UWP fornece muitos serviços, como
uma loja de aplicativos centralizada, um ambiente de execução (AppContainer) e um conjunto de APIs do
Windows para uso, substituindo o Win32 (WinRT). Os aplicativos podem ser escritos em C ++, C #,
Visual Basic e JavaScript.


<div align="center">
  <img src="https://user-images.githubusercontent.com/61476935/117233533-ac0e1c80-adf9-11eb-89b5-afc38d8aee77.png">
</div>

Cada implementação do .NET inclui os seguintes componentes:


  <ul>
   <li>Um ou mais runtimes. Exemplos: .NET Framework CLR, .NET 5 CLR.</li>

   <li>Uma biblioteca de classes. Exemplos: .NET Framework biblioteca
   de classes base, biblioteca de classes base do .NET 5.</li>

   <li>Opcionalmente, uma ou mais estruturas de aplicativo. Exemplos:
   ASP.net, Windows Forms e Windows Presentation Foundation (WPF)
   estão incluídos no .NET Framework e no .NET 5.</li>

   <li>Opcionalmente, ferramentas de desenvolvimento. Algumas ferramentas
   de desenvolvimento são compartilhadas entre várias implementações.</li>
  </ul>
  

 <h2>
    Biblioteca de Classes do .NET
 </h2>
 
  
 As Bibliotecas de classes são o conceito de biblioteca compartilhada do .NET. Eles permitem a composição 
 de funcionalidades úteis em módulos que podem ser usados por aplicativos distintos. Eles também podem ser
 usados como um meio de carregar funcionalidades que não são necessárias ou não são conhecidas na
 inicialização do aplicativo. As bibliotecas de classes são descritas usando o formato de arquivo
 .NET Assembly.
  
 <ul>
   <li>
     específicas da plataforma, como Base Class Library para o .Net Framework, Core Library para o .Net Core e
     Mono Class Library para o Xamarin, (conforme tabela abaixo);
   </li>
   <li>
     bibliotecas de classes portáteis – são APIs (Application Programming Interface) que podem ser usadas para
     vários ambientes (Windows, Linus, iOS);
   </li>
   <li>
     bibliotecas de classe .Net Standard – que é a união entre os dois primeiros tipos de bibliotecas.[
   </li>
 </ul>
  
  
 <h2>
    Processo de Compilação
 </h2>
 

Como foi anteriormente mencionado, o .NET fornece suporte para multiplas linguagens; uma
vez que o código escrito em uma dessas linguagens é compilado, todo um processo de leitura
e interpretação também é executado. Esse processo consiste na transposição da linguagem usada
para uma linguagem intermediaria, e com isso gera-se um arquivo com o código convertido. O arquivo
executável(.exe) gerado leva a nomeclatura de assembly dentro do C#.

 
<div align="center">
  <img width="90%" src="https://user-images.githubusercontent.com/61476935/117234352-34d98800-adfb-11eb-9d64-53d3400667b5.png">
</div>
 

O executável, agora carregando o programa em uma Common Intermediate Language ou CIL, passa
a ser lido pelo Common Language Runtime(CLR) em um processo chamado de Just-in-Time(JIT).
O CLR nada mais é que a máquina virtual responsável por facilitar o processo de execução
dos códigos geridos no .NET. Já o JIT é o responsável por tratar essa informação e convertê-la
em machine code, este sendo por sua vez é interpretado pelo sistema operacional.
  

  
<div align="center">
   <h1>Ambiente de Desenvolvimento</h1>
</div>

 
O .NET é ambienteado e desenvolvido no Visual Studio, IDE desenvolvida pela Microsoft com o intuito de atender
exclusivamente às especificações do ambiente .NET. Suportando linguagens como VB(Visual Basic), C#, C++, F# e
Python, o Visual Studio é bastante versátil, sendo companhia constante do desenvolvedor .NET. Além disso, ele
suporta diversos tipos de interações com o sistema operacional, permitindo desenvolver uma série de tipos de
aplicações, sejam voltadas para os ambientes de Console, Windows Form, Web ou mesmo Mobile.

 




 
