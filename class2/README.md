### Learned content

* *Removing the styles that the browser automatically creates* 
* *How static, relative, and absolute element placement works*
* *How to position the header of our page*

* *Using CSS, apply borders to the elements.*
* *The different types of edges.*
* *Leaving the rounded edge.*

* *Some CSS pseudo-classes*
* *hover, when the user hovers the cursor over the element
active, when an element is being activated by the user*
* *Changing the color of the text and / or the border of an element, when the user hovers the cursor over it*
* *Changing the color of an element's border when it is being activated by the user*

* *The footer tag, for the footer of our page* 
* *That, with CSS, we can place a background image in an element*
* *When placing a background image on an element, the CSS, by default, copies and pastes the image several times until it occupies the entire space of the element*
* *The Unicode table*

* *O textarea, para entradas de texto de mais de uma linha*
* *O input do tipo radio*
* *Como agrupar vários input do tipo radio, impedindo que mais de um input seja selecionado*
* *O input do tipo checkbox*
* *Que podemos criar um input dentro de um label, assim associando-os*
* *Mais estilizações para a nossa página*
* *Como funciona a hierarquia no CSS*
* *O select, que é seletor, um campo de seleção de um item, e o option, que representa cada opção do seletor*

* *A criar uma tabela HTML*
    * *A tag table, que representa a tabela*
    * *A tag tr, que representa a linha da tabela*
   * *A tag td, que representa a célula da tabela*
   * *A tag thead, que representa o cabeçalho da tabela*
   * *A tag tbody, que representa o corpo da tabela*
   * *A tag th, que representa a célula do cabeçalho da tabela*
   * *A tag tfoot, que representa o rodapé da tabela*
* *A estilizar a tabela*


* *Aula 4*
    * Seletores avançados CSS
       *Seletor >, para acessar os filhos de determinado elemento. Por exemplo, para acessar todos os p dentro de main:*
            main > p {
            }       
        *Seletor +, para acessar o primeiro irmão de determinado elemento. Por exemplo, para acessar o primeiro p após um img:*
            img + p {
            }
        *Seletor ~, para acessar todos os irmãos de determinado elemento. Por exemplo, para acessar todos os p após um img:*
            img ~ p {
            }
        *Seletor not, para acessar os elementos, exceto algum. Por exemplo, para acessar todos os p dentro de main, exceto o p que tem id missao:*
            main p:not(#missao) {
            }
    * Como fazer contas com CSS, com a propriedade calc