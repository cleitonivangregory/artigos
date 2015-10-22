# Atomic Design
Cleiton Ivan Gregory (Unoesc Chapecó)</br>
{cleitonivangregory@gmail.com}
####Resumo:
A medida que queremos melhor nossos processos de criação pensamos em melhor nosso métodos. 
Assim vêm sendo pensando já que as mudanças contínuas no âmbito de desenvolvimento de sistemas, como a procura por velocidade e qualidade no desenvolvimento e também necessidade de desenvolvimento responsivo surgiu uma metodologia capaz de criar e desenvolver layouts para esses sistemas cada vez mais complexos. Essa metodologia, criada pro Brad Frost, chama-se Atomic Design.
####1) O que é?
Atomic Design é uma metodologia de criação aproximada da química e é baseada em 5 etapas distintas: átomos, moléculas, organismos, templates e por fim, páginas.
####2) Como funciona
Brad Frost subdividiu o processo em 5 passos:
#### Átomos
São os elementos mínimos presentes em um sistema. Basicamente, são as tags HTML.
#####Exemplos:
um botão, um label, um input de telefone, uma imagem.
#### Moléculas
Somam-se dois ou mais átomos e forma-se uma molécula. E é isso, um conjunto de átomos resulta numa molécula do seu layout.
Aqui, as moléculas já começam a adquirir propriedades específicas voltados para o contexto do sistema.
#####Exemplos:
um mecanismo de busca formado pelos átomos de input e botão.
#### Organismos
São vistos como o agrupamento de moléculas que possuem um mesmo propósito dentro do sistema.
#####Exemplo:
Um bom exemplo para organismo é a barra de menu superior, geralmente organizada com uma logo, um menu com link e uma pesquisa. 
#### Templates
Nesse momento sai um pouco a química e entra o que faz sentido aos clientes. Juntando vários organismos já dá para se ter uma ideia como poderá ficar uma das páginas do sistema. É nesse momento que começamos a visualizar o projeto. Os templates trazem todo um contexto e sentido para os organismos.
#####Exemplo: 
![Template](http://bradfrost.com/wp-content/uploads/2013/06/template1.jpg)
#### Páginas
As páginas são as etapas posteriores aos templates. Templates melhorados forma as páginas. Com as páginas devidamente configuradas é possível fazer uma validação com o cliente e assim, entregar o produto final.
#####Exemplo:
![Template](http://bradfrost.com/wp-content/uploads/2013/06/page1.jpg)
####3) Para que usar
- Porque produz um sistema mais consciente.
- O design e o cliente conseguem ver melhor o sistema.
- O sistema tende a ter escabilidade.
- Reuso de componentes.
- Tempo de manutenção menor.

#####4) Onde usar?
Pode-se usar em qualquer sistema que vier a ser feito. Porém é mais aplicável em sistemas mais complexo e onde mudanças serão mais contínuas.

#####5) Referências
[http://tableless.com.br/o-que-e-design-atomic/](http://tableless.com.br/o-que-e-design-atomic/)</br>
[http://pt.slideshare.net/bradfrostweb/atomic-design](http://pt.slideshare.net/bradfrostweb/atomic-design)</br>
[http://arquiteturadeinformacao.com/mobile/atomic-design-redesenhando-os-entregaveis-de-designers-e-desenvolvedores/](http://arquiteturadeinformacao.com/mobile/atomic-design-redesenhando-os-entregaveis-de-designers-e-desenvolvedores/)