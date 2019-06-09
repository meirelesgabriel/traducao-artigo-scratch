# Tutorial de Scratch para cientistas da computação iniciantes
Tradução de um tutorial de scratch, escrito por David J. Malan, para iniciantes na programação

## Introdução
A maioria das linguagens de programação, à primeira vista, parecem grego para os olhos desacostumados, um amálgama de inglês e uma sintaxe estranha. Considerem, por exemplo, o programa abaixo escrito numa linguagem chamada Java.

```
class Hello
{
  public static void main(String [] args)
  {
    System.out.println(“hello, world!”);
  }
}
```

Tudo o que o programa acima faz, quando executado, é exibir “hello, world!” na tela do usuário. Vocês devem ter adivinhado só de bater o olho no código – ignorando tudo que não fazia sentido! Mas e quanto às chaves? E o que é System.out? O que significa class Hello? E public static void main(String [] args)? É melhor não abordarmos esse tema neste momento.

Basta dizer que, quando se trata de aprender a programar, há uma curva de aprendizagem com linguagens tipo Java. Antes de começar a resolver problemas, você primeiramente deve aprender a ler e escrever numa linguagem nova, mesmo que a tarefa seja relativamente simples (por ex. “hello, world!”). E enquanto que vocês podem perfeitamente entender um estrangeiro que pronuncie mal algumas palavras em português, computadores não são nem um pouco piedosos quando se trata de erros. Deixem faltar um ponto-e-vírgula e pronto, o programa acima já não vai funcionar!

Aprender a programar, no final das contas, é aprender a pensar logicamente e a abordar problemas de modo metódico. Os blocos construtores com os quais os programadores constroem suas soluções, entretanto, são relativamente simples. São bastante comuns na programação, por exemplo, os “loops” (através dos quais um programa faz algo diversas vezes) e as “condições” (pelas quais um programa somente faz algo sob determinadas circunstâncias). Igualmente comuns são as “variáveis” (servem para que um programa, assim como um matemático, guarde na memória certos valores).

Para muitos estudantes, a sintaxe aparentemente enigmática de linguagens como Java tende a ser uma pedra no caminho do domínio de conceitos relativamente simples como estes. Então antes de enfrentarmos uma linguagem como Java, com as suas chaves e seus pontos-e-vírgulas, voltemos a nossa atenção ao Scratch, “uma nova linguagem de programação que te permite criar as suas próprias animações, jogos, e arte interativa no geral.” Embora originalmente desenvolvido para crianças pelo grupo de pesquisa Lifelong Kindergarten no MIT Media Lab, o Scratch é igualmente útil (e divertido) para cientistas da computação principiantes. Por representar os blocos construtores dos programas com blocos coloridos (peças de quebra-cabeça), o Scratch facilita as coisas diminuindo a complexidade da programação, permitindo assim que o cientista da computação foque em problemas em vez de em sintaxe, e domine conceitos programáticos em vez da sintaxe. A sintaxe, é evidente, virá mais tarde. Mas, por ora, foquemos na programação em si. Quer dizer que a programação, por enquanto, será mais “juntar peças de um quebra-cabeça” do que “escrever em grego”.

Este tutorial introduz os blocos de construção da programação aos cientistas da computação iniciantes através do Scratch. Também assume que você já esteja familiarizado com as funcionalidades do Scratch e, por consequência, tenha uma ideia geral de como programar com o Scratch.

Antes de mais nada, vamos nos focar nas instruções. 

## Statements

Na programação, um statement nada mais é que uma diretiva que diz ao computador para fazer algo. Considerem o statement como se fosse um comando ou uma instrução. No Scratch, todo bloco cujas palavras se assemelhem a um comando é um statement (instrução*).
*A partir deste momento usaremos o termo instrução para nos referirmos ao conceito de statement.
Um bloco desse tipo pode instruir um ator a dizer algo:
 

Outro bloco desses também pode fazer um ator andar até um local qualquer:
  
Às vezes, queremos que uma instrução somente seja executada sob certas condições. Tais condições são definidas em termos de expressões booleanas, assunto que vamos tratar a seguir.
