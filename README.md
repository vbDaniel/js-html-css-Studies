# Front-End Web Development  JavaScript - HTML - CSS -> Studies

**Combo de estudo de como interligar as três  ferramentas  e linguagens corretamente**

## HTML
### O que é o HTML?
HyperText Markup Language, como o próprio nome diz, o HTML é uma linguagem de marcação, usada para estrutar o texto e criar conexões com outros elementos do website. De maneira simplória: "O esqueleto" da página web. Esta marcação é dada em tags.

### Tags
Tags são instruções na linguagem de marcação, tendo uma marca de início e outra de fim para que o navegador possa renderizar uma página. ( < > , </ > ).

### Estrutura padrão 
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title> Titulo da página </title>
</head>
<body>
    
</body>
</html>
```
- **Nota**: Os elementos dados entre < > e </ > são as chamadas tags. 
- Para gerar essa estrutura inicial basta digitar ! no seu editor de texto.
------------------------------------------
### Inline vs Block Elements
Os elementos 


### Criando Listas
- Lista Não Ordenada 
Lista sem numeração, a qual a ordem não importa. Usa-se a tag < ul > e para criar elementos de lista usa-e < li >
``` CSS
<ul>
    <li> Item 1  </li>
    <li> Item 2  </li>
    <li> Item 3  </li>
</ul>
```
- Lista Ordenada
Lista numerada (1,2, 3...), a qual se importa em ordenar. Usa-se a tag < ol > e para criar elementos de lista usa-e < li >

``` CSS
<ol>
    <li> Item 1  </li>
    <li> Item 2  </li>
    <li> Item 3  </li>
</ol>
```
------------------------------------------
### Criando Tabelas
 Inicializada com a tag `<table> `e e struturada em Caption (cabeçalho), thead, tbody e tfood. No "thead" são adicionadas linhas `<tr>` e dentro das linhas são adicionadas colunas `<th> `, para a criação de colunas na tabela. Para adicionar dados na tabela usamos o `<td>`.
  **Legenda:** <br>
    tr:  (table rows) <br>
    th:  (table height) <br>
    td : (table data) <br>
    
 ### Estrutura básica no HTML:
    ``` HTML
          <table>
        <thead>
            <tr>
                <th> </th>
                <th></th>
                <th></th>
            </tr>
        </thead>
        <tbody></tbody>
        <tfoot></tfoot>
    </table>
     ```
Colspan —> Mescla colunas
Rowspan —> Mescla linhas
------------------------------------------
## CSS

  <img width="996" alt="Screen Shot 2021-10-21 at 10 19 17" src="https://user-images.githubusercontent.com/87997848/138285916-6e9203e6-de7a-4f56-8e25-d2685f18374e.png">

Pode se ver o padrao estrutural de um elemento apartir da imagem a cima.

DICA STYLES: 
```CSS
header img
{
border: 1px xolid #808080;
border-radius: 4px; // Arredonda a Borda
}
```
Se almentar exponencialmente  o px de  border-radius forma-se um círculo.


























