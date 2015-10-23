### Artigo de CSS3
### Unoesc Chapecó
### Pós-graduação em Desenvolvimento Web, Cloud e Dispositivos Móveis - WebMob
### Disciplina: HTML5 + CSS3
### Professor: Jean Carlo Nascimento
### Acadêmico(a): Cleiton Ivan Gregory
## Artigo de revisão de CSS3
<hr/>
####Funcionalidade: Text Shadow
#####O que é?
Essa propriedade serve para deixar os textos com sombras.
#####Onde usar:
No atributo text dos elementos da página.
#####Como usar:
```css
seletor { 
  text-shadow: offsetX offsetY raioBlur cor [,offsetX offsetY raioBlur cor];
}
```
#####Exemplo de uso:
```css
seletor { 
  text-shadow: 5 5 5 5 none;
}
```
#####Referência:
[http://www.maujor.com/tutorial/interativo-css3/inc/textshadow.php](http://www.maujor.com/tutorial/interativo-css3/inc/textshadow.php)
<hr/>
####Funcionalidade: gradients
#####O que é?
É um seletor capaz de criar transições entre cores.
#####Onde usar:
Em propriedades que possuam o atributo cor.
#####Como usar:
```css
[propriedade]: linear-gradient([direction<to bottom, to top, to right, to left, to bottom right, etc.>, color-stop1, color-stop2, ...]);
```
#####Exemplo de uso
```css
div {
	background: linear-gradient(to bottom, #fff, #000);
}
```
#####Referência:
[http://www.w3schools.com/css/css3_gradients.asp](http://www.w3schools.com/css/css3_gradients.asp)
<hr/>
####Funcionalidade: @media
#####O que é?
É uma funcionalidade onde se pode alterar visualização de acordo com a media utilizada.
#####Onde usar:
Utiliza-se em 
na definição de visualização especificas para determinadas midias e resoluções.
Como usar:
```css
@media not|only mediatype and (expressions) {
    CSS-Code;
}
```
#####Exemplo de uso:
```css
@media screen and (max-width: 480px) {
    div{
        width:100px;
    }[
}
```
#####Referência:
[http://www.w3schools.com/css/css3_mediaqueries.asp](http://www.w3schools.com/css/css3_mediaqueries.asp)
<hr/>
####Funcionalidade: rotate
#####O que é?
Rotaciona um objeto de acordo com o ângulo definido. 
#####Onde usar:
Pode-se utilizar em qualquer seletor.
#####Como usar:
```css
seletor{
    transform: rotate(angle); /* Rotação 2D */
    transform: rotate3d(x,y,z,angle); /* Rotação 3D */
    transform: rotateX(angle); /* Rotação 3D pelo eixo X*/
    transform: rotateY(angle); /* Rotação 3D pelo eixo Y*/
    transform: rotateZ(angle); /* Rotação 3D pelo eixo Z*/
}
```
#####Exemplo de uso
```css
div {
    transform: rotateX(45deg);
}
```
#####Referência:
[http://www.w3schools.com/css/css3_2dtransforms.asp](http://www.w3schools.com/css/css3_2dtransforms.asp)
<hr/>
####Funcionalidade: Opacity
#####O que é?
É uma propriedade que tem o efeito de transparente. 
#####Onde usar:
Utilizado em elementos de estrutura.
#####Como usar:
```css
seletor { opacity: number|initial|inherit; }
```
#####Exemplo de uso
```css
div { opacity: 0.5 }
```
#####Referência:
[http://www.w3schools.com/cssref/css3_pr_opacity.asp](http://www.w3schools.com/cssref/css3_pr_opacity.asp)
<hr/>
####Funcionalidade: calc
#####O que é?
Funcionalidade para fazer cálculos dentro do css.
#####Onde usar:
Em propriedades que valores.
#####Como usar:
```css
	[propriedade]: calc([expressão]) 
```
##### Exemplo de uso:
```css
	div {
		width: calc(100% - 65px);
	}
```
####Referência:
[http://www.maujor.com/tutorial/css3-funcao-css-calc.php](http://www.maujor.com/tutorial/css3-funcao-css-calc.php)
<hr/>
####Funcionalidade: font-face
#####O que é?
É uma funcionalidade para definir um tipo de fonte em determinado seletor que contenha texto.
#####Onde usar:
Em qualquer texto da página.
#####Como usar:
```css
@font-face {
    font-family: [name];
    src: url([url_arquivo_fonte]);
    font-stretch: [normal|condensed|ultra-condensed|extra-condensed|semi-condensed|expanded|
				   semi-expanded|extra-expanded|ultra-expanded];
	font-style:	 [normal|italic|oblique];
	font-weight: [normal|bold|100|200|300|400|500|600|700|800|900];
	unicode-range:	[unicode-range]
}
```
#####Exemplo de uso:
```css
p {
	font-family: "Lucida Grande", "Lucida Sans", Verdana, Sans-Serif;
	}
```
####Referência:
[http://www.maujor.com/tutorial/css3-@font-face.php](http://www.maujor.com/tutorial/css3-@font-face.php)
<hr/>
####Funcionalidade: Box Sizing
#####O que é?
Utilizado para alterar ou não o tamanho da borda, preenchimento ou margem de algum elemento.
#####Onde usar:
Em elementos que contenham border, pad ou margin.
#####Como usar:
```css
seletor {
	box-sizing: content-box|border-box|initial|inherit; width: x; border: y; float: left; 
}
```
##### Exemplo de uso:
```css
div {
	width: 50px;
	height: 50px;
	padding: 10px;
	border: 1px solid #fff;
	box-sizing: border-box;
}
```
####Referência:
[http://www.w3schools.com/cssref/css3_pr_box-sizing.asp](http://www.w3schools.com/cssref/css3_pr_box-sizing.asp)
<hr/>
####Funcionalidade: Z-index
#####O que é?
O z-index é a funcionalidade que diz a ordem em que o elemento está dentro da página.
#####Onde usar:
Em qualquer elemento html.
#####Como usar:
```css
seletor {
	z-index: [number];
}
```
##### Exemplo de uso:
```css
img {
    position: absolute;
    left: 0px;
    top: 0px;
    z-index: -1;
}
```
####Referência:
[http://www.w3schools.com/cssref/pr_pos_z-index.asp](http://www.w3schools.com/cssref/pr_pos_z-index.asp)
<hr/>
####Funcionalidade: vertical-align 
#####O que é?
Funcionalidade para definir o alinhamento na vertical.
#####Onde usar:
Em qualquer elemento em que se queira definir um alinhamento vertical.
#####Como usar:
```css
seletor {
	vertical-align: [text-top|text-center|text-bottom];
}
```
#####Exemplo de uso:
```css
img.bottom {
    vertical-align: text-bottom;
}
```
####Referência:
[http://www.w3schools.com/cssref/pr_pos_vertical-align.asp](http://www.w3schools.com/cssref/pr_pos_vertical-align.asp)
<hr/>
