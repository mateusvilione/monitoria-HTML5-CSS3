# Aula4

## Css da tabela

```css
table {
   font-family: "Lucida Sans Unicode". "Lucida Grande". sans-serif;
   width: 60%; /* Largura da tabela vai ocupa 90% do tamanho da janela */
   border-collapse: collapse; /* remove o espaçamento entre as células */
   margin: 0 0 100px 0; /* dar espaçamento do conteúdo de baixo */
   /*margin-bottom: 100px;*/
   /*width: 300px;*/
}

tbody { /* corpo da tabela */
   background-color: #aaa;
}

th { /* table header ênfase na célula */
   background-color: #000;
   color: #fff;
}

td { /* Célula da tabela */
   background-color: #ddd;
   /*font-weight: bold;*/
}

td.th { /* td e th vao ser alterados*/
   padding: 5px;
   border: 1px solid #444;
}
```

## HTML da tabela
```html
    <table>
        <caption>Legenda</caption>
        <thead>
           <tr>
              <th>Item 1</th>
              <th>Item 2</th>
              <th>Item 3</th>
           </tr>
        </thead>
        
         <tbody>
           <tr>
              <td>Célula 1</td>
              <td>Célula 2</td>
              <td>Célula 3</td>
           </tr>
           <tr>
              <td>Célula 1</td>
              <td>Célula 2</td>
              <td>Célula 3</td>
           </tr>
           <tr>
              <td>Célula 1</td>
              <td>Célula 2</td>
              <td>Célula 3</td>
           </tr>
        <tbody>
    </table>
```

## Exemplo de tabela com Css

![alt text](https://github.com/mateusvilione/monitoria-HTML5-CSS3/blob/master/Monitoria/1%C2%B0%20Ciclo/Aula4/img/tabela%26css.png "tabela com estilo css")
