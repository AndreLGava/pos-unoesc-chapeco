
#### Unoesc Chapecó
#### Pós-graduação em Desenvolvimento Web, Cloud e dispositivos móveis - WebMob
#### Disciplina: HTML5+CSS3
#### Professor: Jean Carlo Nascimento
#### Acadêmico(a): André Luiz Gava {andrelzgava@gmail.com}
####Atomic Design


###Resumo:

O Atomic Design é uma metodologia que visa revolucionar o desenvolvimento de interfaces gráficas, tal conceito aplica-se para diminuir o tempo de desenvolvimento e seguir um padrão de organização para o projetos. O conceito baseia-se em átomos, moléculas, organismos, template e paginas.

###1) O que é?

O atomic design é uma metodologia utilizada para acelerar o desenvolvimento de novas interfaces web, o conceito baseia-se na ideia de que devemos desenvolver a interface nos baseando das partes menores para as maiores, utilizando os conceitos de átomos, moléculas,organismos, template e por ultimo paginas. Este conceito foi criado por Brad Frost, o qual se inspirou na ideia : " Do que é feito a interface?" e "We’re not designing pages, we’re designing systems of components.— Stephen Hay" ou "Não estamos desenhando paginas, nós estamos desenhando componentes de sistemas" em tradução literal.
 
###2) Como funciona

Baseando-se no conceito do micro para o macro, podemos associar as tags HTML (input, div, textarea, button etc) e fontes, padrões e cores aos átomos, sozinhos e independentes eles não são muito uteis, mas são a base de tudo e quando unificados se tornam mais uteis. A junção de pequenas tags (input em div, link em nav, etc) e outros elementos podemos comparar a moléculas, estes elementos quando unidos possuem mais propriedades de usabilidade e funcionalidade do que somente os átomos, em contra partida os componentes (modal, alert, jumbotron, parallax, panels, breadcrumbs entre outros) como organismos, estes componentes tornam-se reutilizáveis, uma vez que após criados eles possuem uma característica peculiar e unica que pode ser usado em vários projetos, unindo componentes dentro de um determinado padrão temos o template que é mais sólido, tem uma característica bem marcante devido ao padrão e se torna mais fácil de mostrar para o cliente. É através do template que secionando diferentes componentes, criamos as páginas, o conceito é muito util, alguns outros programadores defendem ainda a ideia do bóson de higgs como sendo as variáveis  que utilizamos ao escrever o CSS em SASS, LESS ou STYLUS (preprocessadores CSS). 


###3) Para que usar

Atualmente temos uma grande gama de Frameworks Front-End, porém devido ao grande uso destes projetos, toda a internet vem ganhando cada vez mais uma "cara" muito semelhante, sem contar boa parte dos principais componentes dos principais Frameworks são muito parecidos. O Atomic Design serve como uma metodologia que visa desenvolver template e paginas com qualidade e em tempo menos alem de organizar a ideia para a criação de componentes que possam ser reutilizados em outros projetos, até mesmo criar um framework do 0. Tudo isto permite que tenhamos uma variabilidade maior nas paginas web.

###4) Onde usar?

Podemos utilizar o Atomic Design desde a criação de componentes até a finalização de um grande projeto, basta verificar o tempo disponível e a satisfação com o que já se tem em termos de componentes e templates.

###5) Exemplos:

####Átomos

Input:<br/>
![image](https://raw.githubusercontent.com/AndreLGava/pos-unoesc-chapeco/master/arquivos/input.jpg)<br/>

Botão:<br/>
![image](https://raw.githubusercontent.com/AndreLGava/pos-unoesc-chapeco/master/arquivos/botao.jpg)<br/>

outros exemplos em códigos:

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

Label e Input:<br/>
![image](https://raw.githubusercontent.com/AndreLGava/pos-unoesc-chapeco/master/arquivos/mol_input.jpg)<br/>

outros exemplos em códigos:

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

Alert Boostratp:<br/>
![image](https://raw.githubusercontent.com/AndreLGava/pos-unoesc-chapeco/master/arquivos/alert.jpg)<br/>

Form Bootstrap:<br/>
![image](https://raw.githubusercontent.com/AndreLGava/pos-unoesc-chapeco/master/arquivos/form.jpg)<br/>

outros exemplos em códigos:

```css

jumbotron bootstrap:
  <div class="jumbotron">
    <h1>Fala Suissa, acho que você vai odiar esse exemplo aqui :/</h1>
    <p>...</p>
    <p><a class="btn btn-primary btn-lg" href="#" role="button">Aprenda +</a></p>
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

Abaixo um wireframe mostrando a utilização de componentes para compor a estrutura e arquitetura de uma página web:

![image](https://raw.githubusercontent.com/AndreLGava/pos-unoesc-chapeco/master/arquivos/wireframe.jpg)<br/>
Outros exemplos de template com vários componentes de frameworks:<br/>
Metronic{http://www.keenthemes.com/preview/metronic/theme/templates/admin3/}<br/>
Bootstrap demo{http://getbootstrap.com/examples/theme/}



####Páginas
Enfim a ultima etapa de desenvolvimento, a página web:
![image](https://raw.githubusercontent.com/AndreLGava/pos-unoesc-chapeco/master/arquivos/pagina.jpg)<br/>
Outros exemplos de páginas construidas a partir de componentes de frameworks<br/>
por Fundation<br/>
{http://foundation.zurb.com/templates/banner-theme.html}<br/>
por Fundation<br/>
{http://foundation.zurb.com/templates/portfolio-theme.html}<br/>



####6) Referências
[http://bradfrost.com/blog/post/atomic-web-design/](http://bradfrost.com/blog/post/atomic-web-design/) <br/>
[http://tableless.com.br/o-que-e-design-atomic/](http://tableless.com.br/o-que-e-design-atomic/) <br/>
[http://nomadev.com.br/passo-a-passo-como-desenvolver-com-atomic-design-mobile-first-e-stylus/](http://nomadev.com.br/passo-a-passo-como-desenvolver-com-atomic-design-mobile-first-e-stylus/) <br/>
[http://nomadev.com.br/atomic-design-por-que-usar/](http://nomadev.com.br/atomic-design-por-que-usar/) <br/>
[https://www.youtube.com/watch?v=84LZyZsTiaA](https://www.youtube.com/watch?v=84LZyZsTiaA) <br/>
[http://www.wirify.com/wp/wp-content/uploads/2011/02/CNN-International-Original-vs-Wirify-wireframe1.jpg](http://www.wirify.com/wp/wp-content/uploads/2011/02/CNN-International-Original-vs-Wirify-wireframe1.jpg) <br/>
[http://foundation.zurb.com/templates/banner-theme.html](http://foundation.zurb.com/templates/banner-theme.html)<br/>
[http://getbootstrap.com/examples/theme/](http://getbootstrap.com/examples/theme/)<br/>
[http://foundation.zurb.com/templates/banner-theme.html](http://foundation.zurb.com/templates/banner-theme.html)<br/>
[http://foundation.zurb.com/templates/portfolio-theme.html](http://foundation.zurb.com/templates/portfolio-theme.html)<br/>
