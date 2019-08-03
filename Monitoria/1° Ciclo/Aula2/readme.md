# Aula2

## Listas

### Lista ordenada - (Ordered List)
```html
<ol>
  <li>Item 1</li> <!-- item da lista (list item) -->
  <li>Item 2</li>
  <li>Item 3</li>
</ol>
```

### Exemplo - Lista ordenada
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ol>

### Lista não ordenada - (Unordered List)
```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```

### Exemplo - Lista não ordenada
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>

### Listas aninhadas
```html
<ol>
  <li>Item 1</li>
  <li>Item 2      <!-- A tag de fechamento </li> não é fechada aqui! -->
    <ol>
      <li>Item 1 subitem</li>
      <li>Item 2 subitem</li>
      <li>Item 3 subitem</li>
    </ol>
  </li>                <!-- fechando a tag </li> -->
  <li>Item 3</li>
</ol>
```

### Exemplo - Listas aninhadas
<ol>
    <li>Item 1</li>
    <li>Item 2          <!-- A tag de fechamento </li> não é fechada aqui -->
        <ol>
            <li>Item 1 subitem</li>
            <li>Item 2 subitem</li>
            <li>Item 3 subitem</li>
        </ol>
    </li>               <!-- fechando a tag </li> -->
    <li>Item 3</li>
</ol>

--- 

## Tabela - table
```html
<table>  <!-- Tabela -->
    <caption> Legenda </caption> <!-- legenda da tabela -->
    <thead> <!-- Bloco de linhas que descreve os cabeçalhos de uma tabela -->
        <tr> <!-- linha da tabela -->
            <th>ID</th> <!-- célula de cabeçalho em uma tabela -->
            <th>célula</th>
        </tr>
    </thead>
    <tbody> <!-- Bloco de linhas que descreve os dados da tabela -->
        <tr> <!-- linha da tabela -->
            <td>1</td> <!-- célula de dados da tabela -->
            <td>Item 1</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Item 2</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Item 3</td>
        </tr>
    </tbody>
</table>
```
### Exemplo - tabela
<table>
    <caption> Legenda </caption> 
    <thead>
        <tr>
            <th>ID</th>
            <th>célula</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>Item 1</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Item 2</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Item 3</td>
        </tr>
    </tbody>
</table>

## Como funciona uma tabela

![alt text](https://preview.c9users.io/mateusvilione/html/Monitoria/1Ciclo/Aula2/img/tabela_html.png "explicação da tabela")