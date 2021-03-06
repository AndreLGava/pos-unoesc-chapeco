
#### Unoesc Chapecó
#### Pós-graduação em Desenvolvimento Web, Cloud e dispositivos móveis - WebMob
#### Disciplina: HTML5+CSS3
#### Professor: Jean Carlo Nascimento
#### Acadêmico(a): André Luiz Gava {andrelzgava@gmail.com}
### Artigo de revisão de CSS3
### Funcionalidade: Transform 2D — Translate
##### O que é?
O método translate da propriedade Transform, permite que posamos aplicar movimento a qualquer elemento DOM em um espaço 2D e 3D. O elemento se deslocará pelo espaço movendo-se nas coordenadas x e y. 
##### Onde usar:
Em qualquer elemento DOM HTML.
##### Como usar:
```css

seletor { transform: translate(x, y); }

```
##### Exemplo de uso
A sintaxe geral para mover objetos é indicada da seguinte forma:

```css
seletor {
  -webkit-transform: translate(40px, 0px);
  -moz-transform: translate(40px, 0px);
  -o-transform: translate(40px, 0px);
  -ms-transform: translate(40px, 0px);
  transform: translate(40px, 0px);
} 


```
#### Referencia:
[http://www.maujor.com/tutorial/interativo-css3/] (http://www.maujor.com/tutorial/interativo-css3/)<br>
[http://beta.theexpressiveweb.com/#!/css3-transforms] (http://beta.theexpressiveweb.com/#!/css3-transforms)<br>
[http://www.w3schools.com/css/css3_2dtransforms.asp ] (http://www.w3schools.com/css/css3_2dtransforms.asp)


### Funcionalidade: Animation
##### O que é?
A propriedade animation nos permite adicionar animações ao conteúdo HTML. Desta forma podemos animar o conteúdo sem javascript ou flash. Podemos aplicar um estilo e transformar em outro gradualmente.
##### Onde usar:
Em qualquer elemento DOM HTML.
##### Como usar:
```css

 @keyframes [funcao] {
    from {[propriedades inciais]: [valor];}
    to {[propriedades finais]: [valor];}
}

[element, classe ou id] {
    animation-name: [funcao]; 
}

```
##### Exemplo de uso
A sintaxe geral para animar objetos é indicada da seguinte forma

```css
@keyframes example {
    from {background-color: red;}
    to {background-color: yellow;}
}

div {
    width: 100px;
    height: 100px;
    background-color: red;
    animation-name: example; 
    animation-duration: 4s;
}



```
#### Referencia:
[http://beta.theexpressiveweb.com/#!/css3-transforms ] (http://beta.theexpressiveweb.com/#!/css3-transforms )<br>
[http://www.w3schools.com/css/css3_animations.asp ] (http://www.w3schools.com/css/css3_animations.asp )

### Funcionalidade: Gradient
##### O que é?
A propriedade gradient nos permite mostrar a transição entre duas ou mais cores especificas sem o auxilio de qualquer arquivo de imagem, esta é uma funcionalidade muito útil pois reduz o tempo para carregamento da página, qualidade de imagem, o tamanho da mesma e a flexibilidade em diferentes telas. Podemos aplicar diferentes gradientes sejam lineares ou radiais em diferentes ângulos e posições.

##### Onde usar:
Em qualquer elemento DOM HTML que possua a opção background.

##### Como usar para diferentes navegadores:
```css
#grad {
  background: -webkit-radial-gradient([cor], [cor] [, …]);
  background: -o-radial-gradient([cor], [cor] [, …]);
  background: -moz-radial-gradient([cor], [cor] [, …]);
  background: radial-gradient([cor], [cor] [, …]);
}


```
##### Exemplo de uso

A sintaxe geral para aplicar o gradiente pode ser utilizada da seguinte forma

```css
#grad {
  background: -webkit-radial-gradient(red, green, blue);
  background: -o-radial-gradient(red, green, blue);
  background: -moz-radial-gradient(red, green, blue);
  background: radial-gradient(red, green, blue); 
}

```
#### Referencia:
[http://beta.theexpressiveweb.com/#!/css3-transforms ] (http://beta.theexpressiveweb.com/#!/css3-transforms )<br>
[http://www.w3schools.com/css/css3_gradients.asp  ] (http://www.w3schools.com/css/css3_gradients.asp )

### Funcionalidade: Shadows

##### O que é?

A propriedade shadow possui dois métodos text-shadow e box-shadow, ambos são utilizados para aplicar o efeito de sombra nas formas e textos dos elementos HTML. Assim como a propriedade gradiente ela facilita o carregamento das páginas por não mais necessitar de imagens para gerar tal efeito. O efeito shadow também permite definir uma cor especifica o que o tornaria mais parecido com um efeito glow.

##### Onde usar:

Em qualquer elemento DOM HTML.

##### Como usar:
```css
 h1 {
    text-shadow: [posição x] [posição y] [desfoque] [cor] ...(, [posição x] [posição y] [desfoque] [cor]);
}

div {
    box-shadow: [posição x] [posição y] [desfoque] [cor] ...(, [posição x] [posição y] [desfoque] [cor]);
}


```
##### Exemplo de uso

A sintaxe geral para aplicar a sombra pode ser utilizada da seguinte forma

```css
h1 {
    text-shadow: 2px 2px 4px #000000;
}

div {
    width: 300px;
    height: 100px;
    padding: 15px;
    background-color: yellow;
    box-shadow: 10px 10px 100px #FF0000;
}


```
#### Referencia:
[http://beta.theexpressiveweb.com/#!/css3-transforms ] (http://beta.theexpressiveweb.com/#!/css3-transforms )<br>
[http://www.w3schools.com/css/css3_shadows.asp  ] (http://www.w3schools.com/css/css3_shadows.asp )

### Funcionalidade: Transition

##### O que é?

A propriedade transition oferece um método simples de animação css de um elemento HTML durante determinado tempo, permitindo criar simples animações  fade, rollover ou outras transições e efeitos sem auxilio de Javascript. Muito similar a Animation CSS, porem menos complicado de implementar, geralmente definindo somente duas coisas (o que animar e em quanto tempo a animação deve acontecer).

##### Onde usar:

Em qualquer elemento DOM HTML através de determinado elemento CSS.

##### Como usar:
```css
div {
    width: [tamanho];
    height: [tamanho];
    background: [cor]];
    -webkit-transition: [propriedade CSS] [tempo em segundos]; /*safari*/
    transition: [propriedade CSS] [tempo em segundos];/*outros*/
}


```
##### Exemplo de uso

A sintaxe geral para aplicar a transição pode ser utilizada da seguinte forma

```css
div {
    width: 100px;
    height: 100px;
    background: red;
    -webkit-transition: width 2s; /* Safari */
    transition: width 2s;
}


```
#### Referencia:
[http://beta.theexpressiveweb.com/#!/css3-transforms ] (http://beta.theexpressiveweb.com/#!/css3-transforms )<br>
[http://www.w3schools.com/css/css3_transitions.asp] (http://www.w3schools.com/css/css3_transitions.asp)


### Funcionalidade: @font-face

##### O que é?

A propriedade @font-face permite que possamos embedar fontes exclusivas na página mesmo que ela não esteja instalada no computados do usuário. Ela torna as páginas mais bonitas e exclusivas, porem se a fonte não existe na maquina ela precisa ser baixada junto com o conteúdo HTML ou seja a página pode por alguns segundos ter uma fonte e assim que o arquivo for carregado a página troca a fonte, algo que pode causar um pouco de confusão para o usuário. Para isso inicialmente precisamos definir o nome da fonte e em seguida definir o caminho.

##### Onde usar:

Em qualquer elemento texto HTML.

##### Como usar:
```css
@font-face {
    font-family: [nome];
    src: url([caminho]+[arquivo].[extensão]);
}


```
##### Exemplo de uso

A sintaxe geral para aplicar a fonte pode ser utilizada da seguinte forma

```css
@font-face {
    font-family: minhaFonte;
    src: url(sansation_light.woff);
}

div {
    font-family: minhaFonte;
}


```
#### Referencia:
[http://beta.theexpressiveweb.com/#!/css3-transforms ] (http://beta.theexpressiveweb.com/#!/css3-transforms )<br>
[http://www.w3schools.com/cssref/tryit.asp?filename=trycss3_font-face_rule_bold] (http://www.w3schools.com/cssref/tryit.asp?filename=trycss3_font-face_rule_bold)


### Funcionalidade: Filter
##### O que é?

A propriedade Filter permite aplicarmos efeitos de cor, gama, exposição, blur, transparência dentre outros a elementos HTML, excelente para tratamento de imagem, ou efeito especifico sem a necessidade de utilizar Javascript ou tratamento com imagens secundarias(css sprite). Os efeitos podem ser obtidos usando os diferentes métodos e repassando diferentes valores.

##### Onde usar:

Em qualquer elemento texto HTML, mas geralmente é mais utilizado no atributo img (imagem).

##### Como usar:
```css
/*desfoque*/
    -webkit-filter: blur([valor]);
    filter: blur([valor]);
/*brilho*/
    -webkit-filter: brightness([valor]); 
    filter: brightness([valor]);
/*contraste*/
    -webkit-filter: contrast([porcentagem]);
    filter: contrast([porcentagem]);
/*Escala de cinza*/
    -webkit-filter: grayscale([porcentagem]);
    filter: grayscale([porcentagem];
/*matiz*/
    -webkit-filter: hue-rotate([valor em graus]);
    filter: hue-rotate([valor em graus]);
/*Inverção*/
    -webkit-filter: invert([porcentagem]);
    filter: invert([porcentagem]);
/*Transparencia*/
    -webkit-filter: opacity([porcentagem]);
    filter: opacity([porcentagem]);
/*Saturação*/
    -webkit-filter: saturate([valor]);
    filter: saturate([valor]);
/*sepia*/
    -webkit-filter: sepia([porcentagem]);
    filter: sepia([porcentagem]);
/*Sombra*/
    -webkit-filter: drop-shadow(8px 8px 10px green);
    filter: drop-shadow(8px 8px 10px green);



```
##### Exemplo de uso

A sintaxe geral para aplicar os métodos da propriedade Filter pode ser utilizada da seguinte forma

```css
.blur {
    -webkit-filter: blur(4px);
    filter: blur(4px);
}

.brightness {
    -webkit-filter: brightness(0.30);
    filter: brightness(0.30);
}

.contrast {
    -webkit-filter: contrast(180%);
    filter: contrast(180%);
}

.grayscale {
    -webkit-filter: grayscale(100%);
    filter: grayscale(100%);
}

.huerotate {
    -webkit-filter: hue-rotate(180deg);
    filter: hue-rotate(180deg);
}

.invert {
    -webkit-filter: invert(100%);
    filter: invert(100%);
}

.opacity {
    -webkit-filter: opacity(50%);
    filter: opacity(50%);
}

.saturate {
    -webkit-filter: saturate(7);
    filter: saturate(7);
}

.sepia {
    -webkit-filter: sepia(100%);
    filter: sepia(100%);
}

.shadow {
    -webkit-filter: drop-shadow(8px 8px 10px green);
    filter: drop-shadow(8px 8px 10px green);
}


```
#### Referencia:
[http://www.w3schools.com/cssref/css3_pr_filter.asp ] (http://www.w3schools.com/cssref/css3_pr_filter.asp )<br>

### Funcionalidade: Media Queries
##### O que é?

Utilizamos os media queries para definir para qual tipo de media determinado código CSS é direcionado, ou seja o utilizamos para definir diferentes tipos de regras para diferentes tipos de dispositivos. Os media queries foram desenvolvidos a partir do atributo media type. Então é um atributo poderoso para que possamos desenvolver interfaces adaptáveis e flexíveis a diferentes tipos de dispositivos e telas. Um atributo poderoso para evitar retrabalho de desenvolvedores e velocidade da aplicação.

##### Onde usar:

Geralmente é mais utilizado para criar classes mais genericas, como grids e outros.

##### Como usar:
```css

@media screen and (min-width: [tamanho minimo]) and (max-width: [tamanho maximo]) { 
[elemento, classe ou id] { 
  [atributo]: [valor]; 
} 

```
##### Exemplo de uso

A sintaxe geral para aplicar os métodos da propriedade Filter pode ser utilizada da seguinte forma

```css

@media screen and (min-width: 600px) and (max-width: 900px) { 
.tres { background: #9CF; } 
span.bt600-900 { display: inline-block; }
 } 

```
#### Referencia:
[http://www.devmedia.com.br/utilizando-css-media-queries/27085] (http://www.devmedia.com.br/utilizando-css-media-queries/27085 )<br>
[http://beta.theexpressiveweb.com/#!/css3-media-queries] (http://beta.theexpressiveweb.com/#!/css3-media-queries)<br>


### Funcionalidade: Perspective 
##### O que é?

A propriedade perspective nos permite adicionar perspectiva ao elemento HTML, ela se parece mais com uma inclinação e deformação do elemento em questão, mas pode ser muito útil para páginas que queiram ter uma estilização de efeito especial ou até mesmo um pequeno game.


##### Onde usar:

Em qualquer elemento texto HTML.

##### Como usar:
```css

[elemento, classe ou id] {
    -webkit-perspective: [valor]; /* Chrome, Safari, Opera */
    perspective:  [valor];;
}


```
##### Exemplo de uso

A sintaxe geral para aplicar os métodos da propriedade perspective pode ser utilizada da seguinte forma

```css
div {
    -webkit-perspective: 500px; /* Chrome, Safari, Opera */
    perspective: 500px;
}

```
#### Referencia:
[http://www.w3schools.com/cssref/css3_pr_perspective.asp] (http://www.w3schools.com/cssref/css3_pr_perspective.asp )<br>



### Funcionalidade: Border Radius 
##### O que é?
 
Essa é uma das propriedades CSS3 mais utilizadas, ela é usada para arredondar os cantos de elementos HTML, tornando o layout mais harmônico e visualmente mais agradável aos olhos dos usuários. Antigamente precisávamos utilizar aquivos de imagem para criar os cantos aredondados, se tinha algum outro efeito como sombra já complicava um pouco, utilizar em outros dispositivos era um terror. Esta funcionalidade torna a página mais estável e mais leve.


##### Onde usar:

Em qualquer elemento HTML, geralmente é utizado em Div, Input, Textarea etc.

##### Como usar:
Podemos utilizar assim:
```css

[elemento, classe ou id] {
    border-radius:valor;
}

```
Ou caso gostariamos que as bordas tenham tamanhos diferentes e váriados, podemos fazer assim:

```css

[elemento, classe ou id] {
    border-top-left-radius:valor;
    border-top-right-radius:valor;
    border-bottom-right-radius:valor;
    border-bottom-left-radius:valor;
}

```
##### Exemplo de uso

Para utilizar podemos simplesmente declarar assim:

```css
.panel {
    border-radius:valor;
}

```
#### Referencia:
[http://www.w3schools.com/cssref/css3_pr_border-radius.asp] (http://www.w3schools.com/cssref/css3_pr_border-radius.asp )<br>
