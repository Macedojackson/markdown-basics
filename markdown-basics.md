#Os básicos de Markdown
O markdown permite você escrever um formato de texto fácil de ler e fácil de escrever, que converte para HTML válido para visualização no GitHub.

## 1.Escrita Básica

###**Parágrafos**
Parágrafos em Markdown são só uma ou mais linhas de texto consecutivo seguido por uma ou mais linha em branco.
Em 2 de julho, uma nave de alienígena entrou na órbita da terra e implantaram várias dezenas em forma de pires nave espacial "destruidor", a cada 15 milhas (24 quilômetros) de largura.
Em 3 de julho, os cavaleiros negros, um batalhão do corpo da marinha F/A-18 vespões, participaram de um assalto em um destruidor perto da cidade de Los Angeles.
###**Cabeçalhos**
Você pode criar um título adicionando um ou mais símbolos # antes do cabeçalho do seu texto. O número de # que você usar vai determinar o tamanho do título.

<code>#</code> O maior título (uma hl tag)

<code>##</code> O segundo maior título (uma h2 tag)

<code>######</code> O sexto maior título (uma h6 tag)

###**Citações**
Você pode indicar citações com um >.

Nas palavras de Abraão Lincoln:

<code>></code> Perdoa meu francês

###**Estilo de texto**
Você pode fazer o texto em negrito ou itálico.

<code>* Este texto vai ser em itálico *</code>

<code>** Este texto vai ser em negrito **</code>

Ambos, negrito e itálico podem usar um ou outro, um * ou um _ ao redor do texto para estilo. Isso permite você combinar ambos, negrito e itálico se necessário.

<code>** Todo mundo <code>_ deve _</code> assistir a reunião às 5 horas hoje. **</code>

## 2.Listas

###**Listas não ordenada**
Você pode fazer uma lista não ordenada precedendo itens de lista com um ou outro, um * ou um -.

<code>*</code> Item

<code>*</code> Item

<code>*</code> Item

<code>-</code> Item

<code>-</code> Item

<code>-</code> Item

###**Listas ordenadas**
Você pode fazer uma lista ordenada precedendo itens de lista com um número.

1. Item 1

2. Item 2
 
3. Item 3

###**Listas aninhadas**
Você pode criar listas aninhadas recuando itens de lista com dois espaços.

1. Item 1
  1. Uma inferência para o item acima.
  2. No entanto um outro ponto para considerar.
2. Item 2

  * Uma inferência que não necessita ser ordenada.
 
     * Isso está recuado quatro espaços, porque está dois espaços a mais do que o item acima.
    
     * Você pode querer considerar fazendo uma nova lista.
    
3. Item 3

## 3.Formatação de código

###**Formatos em linha**
Use acentos graves individuais (`) para formatar texto em um formato mono espaço especial. Tudo dentro dos acentos graves aparecem como está, sem nenhuma outra formatação especial.

<code>Aqui está uma ideia: por que nós não pegamos o 'projeto superior' e transformamos ele em um '<code>** razoável </code>** projeto'</code>

###**Múltiplas linhas**
Você pode usar acentos graves triplo(` ` `) para formatar como seu próprio bloco distinto.
>Confira este programa organizado que eu escrevi:

` ` `

X= 0

x= 2 + 2

qual é x

` ` `

## 4.Ligações

Você pode criar uma ligação em linha envolvendo a ligação de texto em colchetes( [ ] ), e em seguida envolvendo a ligação em parênteses( ( ) ).
Por exemplo, para criar um hyperlink para www.github.com, com uma ligação de texto que diz, Visite o GitHub!, você escreveria isso em Markdown: [Visite o GitHub!] (www.github.com).

