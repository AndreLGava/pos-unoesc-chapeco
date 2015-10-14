
#### Unoesc Chapecó
#### Pós-graduação em Desenvolvimento Web, Cloud e dispositivos móveis - WebMob
#### Disciplina: HTML5+CSS3
#### Professor: Jean Carlo Nascimento
#### Acadêmico(a): André Luiz Gava
### Artigo de revisão de CSS3
##### Funcionalidade: Transform 2D — Translate
##### O que é?
O método translate da propriedade Transform, permite que posamos aplicar movimento a qualquer elemento DOM em um espaço 2D e 3D. O elemento se deslocará pelo espaço movendo-se nas coordenadas x e y. 
##### Onde usar:
Em qualquer elemento DOM HTML.
##### Como usar:
```css
seletor { transform: translate(x, y); }

```
##### Exemplo de uso
A sintaxe geral para mover objetos é indicada da seguinte forma

```css
seletor {
  -webkit-transform: translate(40px, 0px);
  -moz-transform: translate(40px, 0px);
  -o-transform: translate(40px, 0px);
  -ms-transform: translate(40px, 0px);
  transform: translate(40px, 0px);
} 


```
### Referencia:
[http://www.maujor.com/tutorial/interativo-css3/] (http://www.maujor.com/tutorial/interativo-css3/)<br>
[http://beta.theexpressiveweb.com/#!/css3-transforms] (http://beta.theexpressiveweb.com/#!/css3-transforms)<br>
[http://www.w3schools.com/css/css3_2dtransforms.asp ] (http://www.w3schools.com/css/css3_2dtransforms.asp)


##### Funcionalidade: Animation
##### O que é?
A propriedade animation permite que possamos adicionar animações ao conteúdo HTML. Desta forma podemos animar o conteúdo sem javascript ou flash. Podemos aplicar um estilo ao outro gradualmente.
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
### Referencia:
[http://beta.theexpressiveweb.com/#!/css3-transforms ] (http://beta.theexpressiveweb.com/#!/css3-transforms )<br>
[http://www.w3schools.com/css/css3_animations.asp ] (http://www.w3schools.com/css/css3_animations.asp )

##### Funcionalidade: Gradient
##### O que é?
A propriedade gradient nos permite mostrar a trasição entre duas ou mais cores especificas sem o auxilio de qualquer arquivo de imagem, esta é uma funcionalidade muito útil pois reduz o tempo para carregamento da página, qualidade de imagem, o tamanho da mesma e a flexibilidade em diferentes telas. Podemos aplicar diferentes gradientes sejam lineares ou radiais em diferentes ângulos e posições.
##### Onde usar:
Em qualquer elemento DOM HTML que possua a opção background.
##### Como usar:
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
### Referencia:
[http://beta.theexpressiveweb.com/#!/css3-transforms ] (http://beta.theexpressiveweb.com/#!/css3-transforms )<br>
[http://www.w3schools.com/css/css3_gradients.asp  ] (http://www.w3schools.com/css/css3_gradients.asp )

##### Funcionalidade: Shadows

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
### Referencia:
[http://beta.theexpressiveweb.com/#!/css3-transforms ] (http://beta.theexpressiveweb.com/#!/css3-transforms )<br>
[http://www.w3schools.com/css/css3_shadows.asp  ] (http://www.w3schools.com/css/css3_shadows.asp )
