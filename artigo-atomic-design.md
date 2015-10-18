
#### Unoesc Chapecó
#### Pós-graduação em Desenvolvimento Web, Cloud e dispositivos móveis - WebMob
#### Disciplina: HTML5+CSS3
#### Professor: Jean Carlo Nascimento
#### Acadêmico(a): André Luiz Gava {andrelzgava@gmail.com}
####Atomic Design


###Resumo:

O Atomic Design é uma metodologia que visa revolucionar o desenvolvimento de interfaces graficas, tal conceito aplica-se para diminiur o tempo de desenvolvimento e seguir um padrão de organização para o projetos. O conteit baseia-se em atomos, moleculas, organismos, templates e paginas.

###1) O que é?

O atomic design é uma metodologia utilizada para acelerar o desenvolvimento de novas interfaces web, o conceito baseia-se na ideia de que devemos desenvolver a interface nos baseando das partes menores para as maiores, utilizando os conceitos de atomos, moleculas,organismos, templates e por ultimo paginas. Este conceito foi criado por Brad Frost, o qual se inspirou na ideia : " Do que é feito a inteface?" e "We’re not designing pages, we’re designing systems of components.—Stephen Hay" ou "Não estamos desenhando paginas, nós estamos desenhando componentes de sistemas" em tradução literal.
 
###2) Como funciona

Baseando-se no conceito do micro para o macro, podemos associar as tags HTML (input, div, textarea, button etc) e fontes, padrões e cores aos atomos, sozinhos e independentes eles não são muito uteis, mas são a base de tudo e quando unificados se tornam mais uteils. A junção de pequenas tags (input em div, link em nav, etc) e outros elementos podemos comparar a móleculas, estes elementos quando unidos possuem mais propriedades de usabilidade e funcionalidade do que somente os atomos, em contra partida os componentes (modal, alert, jumbotron, parallax, panels, breadcrumbs entre outros) como organismos, estes componentes tornam-se reutilizaveis, uma vez que após criados eles possuem uma caracteristica peculiar e unica que pode ser usado em varios projetos, unindo componentes dentro de um determinado padrão temos o template que é mais sólido, tem uma caracteristica bem marcante devido ao padrão e se torna mais facil de mostrar para o cliente. É atravéz do template que secionando diferentes componentes, criamos as páginas, o conceito é muito util, alguns outros programadores defendem ainda a ideia do boson de higgs como sendo as variaveis  que utilizamos ao escrever o CSS em SASS, LESS ou STYLUS (preprocessadores CSS). 


###3) Para que usar

Atualmente temos uma grande gama de frameworks Front-End, porém devido ao grande uso destes projetos, toda a internet vem ganhando cada vez mais uma "cara" muito semelhante, sem contar boa parte dos principais componentes dos principais frameworks são muito parecidos. O Atomic Design serve como uma metodologia que visa desenvolver templates e paginas com qualidade e em tempo menos alem de organizar a ideia para a criação de componentes que possam ser reutilizados em outros projetos, até mesmo criar um framework do 0. Tudo isto permite que tenhamos uma variabilidade maior nas paginas web.

###4) Onde usar?

Podemos utilizar o Atomic Design desde a criação de componentes até a finalização de um grande projeto, basta verificar o tempo disponivel e a satisfação com o que já se tem em termos de compoentes e templates.

###5) Exemplos:

####Átomos
```css
HTML :
    <input id="textinput" name="textinput" type="text" placeholder="placeholder">
    
    <select id="selectbasic" name="selectbasic">
          <option value="1">Option one</option>
          <option value="2">Option two</option>
    </select>

arquivos:
      cookie.otf

CSS:
    float: right;




```
####Moléculas
```css
HTML:
      <form>
        <div >
          <input type="text"  placeholder="Buscar">
        </div>
        <button type="submit">Enviar</button>
      </form>

css:
      img  {
          float: right;
      }
```

####Organismos
```css

jumbotron bootstrap:
  <div class="jumbotron">
    <h1>Fala Suissa, acho que você vai odiar esse exemplo aqui :/</h1>
    <p>...</p>
    <p><a class="btn btn-primary btn-lg" href="#" role="button">Aprenda +</a></p>
  </div>
  
alert bootstrap:
  <div class="alert alert-success" role="alert">
    Texto
  </div>


datepicker uikit:
  <form class="uk-form">
      <input type="text" data-uk-datepicker="{format:'DD.MM.YYYY'}">
  </form>
  
panel foundation:

  <div class="panel">
    <h5>Panel normal</h5>
    <p>lorem ipsum dolor sit amet</p>
  </div>

```

####Templates
```css
![image](https://cloud.githubusercontent.com/assets/15130723/10555515/baa9c5ac-7446-11e5-9eac-aadf05215071.png)
Metronic{http://www.keenthemes.com/preview/metronic/theme/templates/admin3/}
Bootstrap demo{http://getbootstrap.com/examples/theme/}

```


####Páginas
```css
![image](https://cloud.githubusercontent.com/assets/15130723/10555516/baafe8f6-7446-11e5-9731-10cb8bd39f16.png)
por Fundation{http://foundation.zurb.com/templates/banner-theme.html}
por Fundation{http://foundation.zurb.com/templates/portfolio-theme.html}

```


####6) Referências
[http://bradfrost.com/blog/post/atomic-web-design/](http://bradfrost.com/blog/post/atomic-web-design/) <br/>
[http://tableless.com.br/o-que-e-design-atomic/](http://tableless.com.br/o-que-e-design-atomic/) <br/>
[http://nomadev.com.br/passo-a-passo-como-desenvolver-com-atomic-design-mobile-first-e-stylus/](http://nomadev.com.br/passo-a-passo-como-desenvolver-com-atomic-design-mobile-first-e-stylus/) <br/>
[http://nomadev.com.br/atomic-design-por-que-usar/](http://nomadev.com.br/atomic-design-por-que-usar/) <br/>
[https://www.youtube.com/watch?v=84LZyZsTiaA](https://www.youtube.com/watch?v=84LZyZsTiaA) <br/>
