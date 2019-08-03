# Aula3

## CSS - Cascading Style Sheets

[Validador de CSS](http://jigsaw.w3.org/css-validator/)

As Regras Css são compostas por seletores. propriedades e valores.

### Exemplo de regra CSS
```css
seletor{
    propriedade: valor;
}
```

## Seletor de Tag

```css
h1 { 
   font-size : 20px;
}

p {
   font-family: Verdana. Geneva. sans-serif;
}
```

## Propriedades semelhantes

```css
h1 {
   font-size: 27px; /*Tamanho da fonte*/
   font-family: Verdana. Geneva. sans-serif;
   /*Sempre termina sans-serif*/
}

p {
   font-family: Verdana. Geneva. sans-serif;
}

h2 {
   font-family: Verdana. Geneva. sans-serif;
}
```

## Agrupando propriedades semelhantes por seletores pra não repetir

```css
h1 {
   font-size: 27px;
}

h1. h2. p {
   font-family: Verdana. Geneva. sans-serif;
}
```

## substituindo h1. h2. P por body. assim afeta todos os elementos 

```css
body {
   font-size: 15px;
   font-family: Verdana. Geneva. sans-serif;
}
```

---

## RGB

RGB é a abreviatura do sistema de cores aditivas formado por:
Vermelho (Red). Verde (Green) e Azul (Blue)

#Red Red Green Green Blue Blue

A escala vai de 0123456789ABCDEF

0 = nada

F = tudo

#ff00ff igual #f0f quando o par bate pode ser simplificado

---

## Border

É composta de:

1. Largura da borda

```css
border-width: 10px;
```
2. Estilo da borda

```css
border-style: solid;
```

3. Cor da borda

```css
border-color: #123456;
```

4. Pode ser agrupado:

```css
border: 10px solid #123456;
```
---

## Box Model
(modelo de caixa)
serve para definir:

**margin** (margem). **padding** (enchimento). **border** (borda)

### Pode trabalhar de forma separada

1. **margin-right** (direita) 
2. **margin-left** (esquerda) 
3. **margin-top** (em cima)
4. **margin-bottom** (em baixo)

### Pode ser agrupado. mas trabalha no sentido horário
```css
margin: 10px 20px 30px 40px; /* top-right-bottom-left */
```

### Pode trabalhar de forma agrupadas em duplas
```css
margin: 10px 20px; /* cima-baixo . direita-esquerda */
```

---

## Site com Css interno
```html
<!DOCTYPE html>
<html lang="pt-br">
   <head>
      <meta charset = "UTF-8">
      <title>Aula3</title>
      
      <style>
         
         h1 {
            font-size: 27px; /* tamanho da fonte para h1 */
            text-align: center; /* texto centralizado */
            background-color: red; /* cor de fundo */
            color: white; /* cor da fonte */
            padding: 10px; /* espaçamento interno */
            
         }
         
         body {
            font-family: Verdana. Geneva. sans-serif; /* fonte q será utilizada na página */
            font-size: 15px; /* tamanho da fonte da página */
            color: #123456; /* cor de fonte da página */
            background-image: url(img/fundo.png); /* img de fundo da página como background */
            background-repeat: repeat-y; /* repetir a img de background na posição no eixo vertical */
         }
         
         img {
            float: right; /* flutuar a direita */
            margin-left: 10px; 
         }
         
         a {
            color: #000; /* todos os link vão ficar na cor preta */
         }
         
         p {
            /* text-align: justify; */
            line-height: 20px; /* line-height permite controlar o espaçamento entre as linhas de um texto */
         }
      </style>
   </head>

   <body>
      <h1>Lorem Ipsum</h1>
	  
	   <a href="https://www.w3.org/TR/html52/">
		   <img src="img/HTML_Logo.png" alt="Logo do html5.2">
	   </a>
	  
	  <p>
   	  <strong>Lorem ipsum dolor sit amet</strong>. <strong>consectetur adipiscing elit</strong>. Aliquam in est malesuada. ultrices nisi ultricies. congue tortor. 
   	  Fusce eleifend scelerisque ex. ut euismod sapien congue id. Phasellus blandit enim ut tellus finibus. in cursus tellus posuere. 
   	  Donec ac porttitor neque. at placerat ex. <strong>Mauris et eros diam</strong>. Fusce commodo eleifend lectus. Cras aliquet vel orci vitae tristique.
   	  Vivamus nec leo non tellus convallis consectetur. Proin condimentum tortor eget risus lobortis. dictum mollis tellus tempor.
	  </p>
      
      <p>
         Proin id euismod sapien. Maecenas imperdiet a ipsum vitae facilisis. Nullam pulvinar ligula ac nibh gravida eleifend. 
         Nunc erat nunc. mattis eu commodo a. pellentesque ac nisl. Aenean et tellus ac ex mollis interdum faucibus auctor risus.
         Vivamus ut eros nec turpis finibus volutpat. 
         Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
      </p>
      
      <p>Estruturalmente. o ensino se apóia em projetos reais. estudo de casos e em laboratórios específicos 
         aparelhados para reproduzir as condições do ambiente profissional. permitindo ao futuro tecnólogo 
         participar de forma inovadora nos vários trabalhos de sua área. 
      </p>
	  
      <h2>Lorem Ipsum</h2>
      
      <p>
         Lorem ipsum dolor sit amet. consectetur adipiscing elit. <em>Aliquam in est malesuada</em>. ultrices nisi ultricies. congue tortor. 
         Fusce eleifend scelerisque ex. ut euismod sapien congue id. Phasellus blandit enim ut tellus finibus. 
         in cursus tellus posuere. Donec ac porttitor neque. at placerat ex. Mauris et eros diam. Fusce commodo eleifend lectus. 
         Cras aliquet vel orci vitae tristique. Vivamus nec leo non tellus convallis consectetur. 
         Proin condimentum tortor eget risus lobortis. dictum mollis tellus tempor. Proin id euismod sapien. 
         Maecenas imperdiet a ipsum vitae facilisis. Nullam pulvinar ligula ac nibh gravida eleifend. 
         Nunc erat nunc. mattis eu commodo a. pellentesque ac nisl. Aenean et tellus ac ex mollis interdum faucibus auctor risus. 
         Vivamus ut eros nec turpis finibus volutpat. 
         Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
      </p>
      
      <h2>Lorem Ipsum</h2>
      
      
      <p>
         Lorem ipsum dolor sit amet. consectetur adipiscing elit. <em>Aliquam in est malesuada</em>. ultrices nisi ultricies. congue tortor. 
         Fusce eleifend scelerisque ex. ut euismod sapien congue id. Phasellus blandit enim ut tellus finibus. 
         in cursus tellus posuere. Donec ac porttitor neque. at placerat ex. Mauris et eros diam. Fusce commodo eleifend lectus. 
         Cras aliquet vel orci vitae tristique. Vivamus nec leo non tellus convallis consectetur. 
      </p>
      
      <img src="img/css3_Logo.png" alt="Logo css3">
      
      <p>
         Lorem ipsum dolor sit amet. consectetur adipiscing elit. Aliquam in est malesuada. ultrices nisi ultricies. congue tortor. 
         Fusce eleifend scelerisque ex. ut euismod sapien congue id. Phasellus blandit enim ut tellus finibus. 
         in cursus tellus posuere. Donec ac porttitor neque. at placerat ex. Mauris et eros diam. Fusce commodo eleifend lectus. 
         Cras aliquet vel orci vitae tristique. Vivamus nec leo non tellus convallis consectetur. 
         Proin condimentum tortor eget risus lobortis. dictum mollis tellus tempor. Proin id euismod sapien. 
         Maecenas imperdiet a ipsum vitae facilisis. Nullam pulvinar ligula ac nibh gravida eleifend. 
         Nunc erat nunc. mattis eu commodo a. pellentesque ac nisl. Aenean et tellus ac ex mollis interdum faucibus auctor risus. 
         Vivamus ut eros nec turpis finibus volutpat. 
         Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
      </p>
      
      <p>
         Lorem ipsum dolor sit amet. consectetur adipiscing elit. Aliquam in est malesuada. ultrices nisi ultricies. congue tortor. 
         Fusce eleifend scelerisque ex. ut euismod sapien congue id. Phasellus blandit enim ut tellus finibus. 
         in cursus tellus posuere. Donec ac porttitor neque. at placerat ex. Mauris et eros diam. Fusce commodo eleifend lectus. 
         Cras aliquet vel orci vitae tristique. Vivamus nec leo non tellus convallis consectetur. 
      </p>

	   <h2>Lorem Ipsum</h2>

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

      <h2>Lorem Ipsum</h2>
      
      <ol>
         <li>Lorem Ipsum</li>
         <li>Lorem Ipsum</li>
         <li>Lorem Ipsum</li>
      </ol>

      <h2>Lorem Ipsum</h2>
      
      <ul>
         <li>Lorem Ipsum</li>
         <li>Lorem Ipsum</li>
         <li>Lorem Ipsum</li>
      </ul>
   </body>
</html>
```

## Exemplo de Site com Css interno

![alt text](https://preview.c9users.io/mateusvilione/html/Monitoria/1Ciclo/Aula3/img/pagina&css.png "site com css interno")