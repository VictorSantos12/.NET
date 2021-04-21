![dot_net_plain_wordmark_logo_icon_146545](https://icon-icons.com/icons2/2415/PNG/128/csharp_original_logo_icon_146578.png)


 <h5>
   O C# é uma linguagem de programção multiparadigma, de tipagem forte e
   com o foco voltado para a  orientação a objetos. Bastante parecida com
   linguagens populares como o Javascript, Java e C++, é bastante enraizada 
   na família de linguagens C.
   Por ser uma linguagem de programação orientada a objeto ou Component
   -oriented, é moderna e de uso simples para quem possui os fundamentos de
   POO bem fixados.
</h5>

<h2>
   Ambiente de Desenvolvimento
</h2>

 <h5>
   O C# é executado de forma direta pelo .NET, ferramenta criada pela 
   Microsoft, composta por um conjunto de bibliotecas que podem ser compartilhadas por diferentes linguagens de
   programação, um compilador e uma máquina virtual. Ela foi projetada para trabalhar com várias linguagens
   de programação, como C#. Vb.NET, F# e Delphi Prism, tendo a máquina virtual Common Language Runtime
   (CLR) como o ambiente de execução para todas a linguagens da plataforma. Para que a máquina virtual
   trabalhe com diversas linguagens de programação a CLR não executa diretamente o código da linguagem,
   mas uma linguagem intermediária comum a todas as linguagens da plataforma, a Common Intermediate
   Language (CIL). Para gerar o CIL que será executado na CLR o código de uma linguagem precisa passar por
   um compilador da linguagem (csc.exe).
</h5>

![dot_net_plain_wordmark_logo_icon_146545](https://icon-icons.com/icons2/2415/PNG/128/dot_net_plain_wordmark_logo_icon_146545.png)

<h5>
  Para entender a plataforma .Net de forma mais aprofundada, é preciso definir quais os seus usos. A platafroma é compatível
  com diversos tipos de aplicações, sejam elas: 
</h5>

 <ul>
   <li>Aplicativos Web, APIs da Web e microservices</li>
   <li>Funções sem servidor na nuvem</li>
   <li>Aplicativos nativos da nuvem</li>
   <li>Aplicativos móveis</li>
   <li>Aplicativos da área de trabalho</li>
   <li>WPF do Windows</li>
   <li>Windows Forms</li>
   <li>UWP (Plataforma Universal do Windows)</li>
   <li>Jogos</li>
   <li>Internet das coisas (IoT)</li>
   <li>Aprendizado de máquina</li>
   <li>Aplicativos de console</li>
   <li>Serviços Windows</li>
  </ul>

  <h5>
    Essa variedade permite que os recursos que a platafroma provê sejam
    utilizados para desenvolver, da mesma forma, coisas diferentes.
  </h5>

  <h2>
    Componentes de arquitetura do .NET
  </h2>

  <h5>
    Um aplicativo .NET é desenvolvido para e é executado em uma ou mais
    implementações do .NET. As implementações do .NET incluem o .NET
    Framework, o .NET 5 (e o .NET Core) e o mono. Além disso, há uma 
    especificação de API comum a várias implementações do .NET que é
    chamada .NET Standard.
  </h5> 

<h2>
  .NET Standard
</h2>

  <h5>
   .NET Standard é um conjunto de APIs que são implementadas pela biblioteca
   de classes base de uma implementação do .NET. De maneira mais formal,
   é uma especificação das APIs do .NET que compõem um conjunto uniforme
   de contratos nos quais você compila seu código. Esses contratos são
   implementados em várias implementações do .NET.
 </h5>

<h2>
  Implementações do .NET
</h2>

<h5>
  Cada implementação do .NET inclui os seguintes componentes:
</h5>

  <ul>
   <li>Um ou mais runtimes. Exemplos: .NET Framework CLR, .NET 5 CLR.</li>

   <li>Uma biblioteca de classes. Exemplos: .NET Framework biblioteca
   de classes base, biblioteca de classes base do .NET 5.</li>

   <li>Opcionalmente, uma ou mais estruturas de aplicativo. Exemplos:
   ASP.net, Windows Formse Windows Presentation Foundation (WPF)
   estão incluídos no .NET Framework e no .NET 5.</li>

   <li>Opcionalmente, ferramentas de desenvolvimento. Algumas ferramentas
   de desenvolvimento são compartilhadas entre várias implementações.</li>
  <ul>
  
<h5>Há quatro implementações do .NET às quais a Microsoft dá suporte:</h5>

  <ul>
   <li>.NET 5 (e .NET Core) e versões posteriores</li>
   <li>.NET Framework</li>
   <li>Mono</li>
   <li>UWP</li>
  </ul>
  
<h2>
  .NET 5
</h2>
  
<h5>
  O .NET 5 é uma implementação de plataforma cruzada do .NET que foi projetada
 para lidar com cargas de trabalho de servidor e nuvem em escala. Ele também dá 
 suporte a outras cargas de trabalho, incluindo aplicativos de desktop. Ele é
 executado no Windows, no macOS e no Linux. Ele implementa .NET Standard, portanto,
 o código que tem como alvo .NET Standard pode ser executado no .NET 5. ASP.NET Core,
 Windows Formse Windows Presentation Foundation (WPF) são executados no .NET 5.
</h5>
  

<h2>
  .NET Framework
</h2>
  

<h5>
 .NET Framework é a implementação original do .NET que existia desde 2002. As
 versões 4,5 e posteriores implementam .NET Standard, portanto, o código que tem 
 como destino .NET Standard pode ser executado nessas versões do .NET Framework.
 Ele contém APIs adicionais específicas do Windows, como APIs para desenvolvimento
 de área de trabalho do Windows com o Windows Forms e o WPF. O .NET Framework é
 otimizado para a compilação de aplicativos da área de trabalho do Windows.
</h5>
  

<h2>
  Mono
</h2>
  

<h5>
  O Mono é uma implementação do .NET que é usada principalmente quando um pequeno
  runtime é necessário. É o tempo de execução que capacita aplicativos Xamarin no
  Android, macOS, iOS, tvOS e watchOS e concentra-se principalmente em uma pequena
  superfície. O Mono também é plataforma para jogos criados com o mecanismo Unity.
</h5>
  

<h2>
  Plataforma Universal do Windows (UWP)
</h2>
  

<h5>
 A UWP é uma implementação do .NET que é usada para criar aplicativos do Windows
 modernos e sensíveis ao toque, bem como software para a IoT (Internet das Coisas). Ele
 foi projetado para unificar os diferentes tipos de dispositivos que você talvez queira
 direcionar, incluindo PCs, tablets, telefones e até mesmo o Xbox. A UWP fornece muitos
 serviços, como um repositório centralizado de aplicativos, um ambiente de execução
 (AppContainer) e um conjunto de APIs do Windows para usar em vez das APIS do Win32
 (WinRT). Os aplicativos podem ser escritos em C++, C#, Visual Basic e JavaScript.
</h5>
  

<h2>
 Runtimes do .NET
</h2>
  

<h5>
 Um runtime é o ambiente de execução de um programa gerenciado. O SO faz parte do
 ambiente do runtime, mas não faz parte do runtime do .NET. Aqui estão alguns exemplos
 de runtimes do .NET:
</h5>
  
   <ul>  
     <li>CLR (Common Language Runtime) para .NET Framework</li>
     <li>CLR (Common Language Runtime) para .NET 5</li>
     <li>.NET Native para a Plataforma Universal do Windows</li>
     <li>
        O runtime Mono para Xamarin.iOS, Xamarin.Android,
        Xamarin.Mac e a estrutura de área de trabalho do Mono
     </li>
   </ul>
    
    
