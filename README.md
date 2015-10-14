
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
