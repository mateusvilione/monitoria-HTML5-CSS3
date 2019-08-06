# Aula1

[Especificação do HTML5](https://www.w3.org/TR/html52/)

Html (*Hypertext Markup Language*) → Linguagem de Marcação de Hipertexto

[Validação de HTML](https://validator.w3.org)

comentário html
```<!-- -->```
---

## Tags

### Tags Pareadas (Paired Tagss)
São tags q abrem e fecham
```html
<p> Parágrafo... </p>
    
<h1> Título 1 </h1>
    
<div> container genérico </div>
```

### Tags não Pareadas (Unpaired Tags)
São tags que não são fechadas
```html
<br>
    
<img src="imagem.png" alt="descrição">
    
<link href="css/estilo.css" rel="stylesheet">
```

---

## Estrutura básica padrão de uma página HTML
```html
<!DOCTYPE html> <!-- informar ao navegador que será HTML5 -->
<html lang="pt-br"> <!-- informar ao navegador que o idioma da página -->
    <head> <!-- cabeçalho -->
        <meta charset="UTF-8">  <!-- unicode transformation format 8 bit -->
        <title>Document</title> <!-- Título que será exibido na aba do navegador -->
    <head>
    
    <body> <!-- corpo da página -->

    </body>
</html>
```

---

## Cabeçalho de nível - H1. H2. H3. H4. H5. H6
```html
<h1>Título 1</h1> <!-- Boa pratica colocar Só um H1 por página -->
<h2>Título 2</h2>
<h3>Título 3</h3>
<h4>Título 4</h4>
<h5>Título 5</h5>
<h6>Título 6</h6>
```
### Exemplo - Cabeçalho de nível
<div>
    <h1>Título 1</h1>
    <h2>Título 2</h2>
    <h3>Título 3</h3>
    <h4>Título 4</h4>
    <h5>Título 5</h5>
    <h6>Título 6</h6>
</div>

---

## Parágrafo - P
```html
<p>
    Lorem ipsum dolor sit amet. consectetur adipiscing elit. Sed iaculis nec erat vel fermentum. Suspendisse ullamcorper orci id turpis tempus placerat. Aliquam quis sem et augue consequat imperdiet venenatis a ipsum. Nulla tempor. lorem quis interdum ullamcorper. ex purus feugiat mi. sit amet consequat felis orci at urna. Donec accumsan maximus risus sit amet molestie. Quisque nec interdum sapien. eu tincidunt neque. Nam eget velit a nisi dignissim gravida vel id libero. Donec fermentum viverra ex sit amet venenatis. Cras tristique sed enim non hendrerit.
</p>
```
### Exemplo - Parágrafo
<div>
    <p>
        Lorem ipsum dolor sit amet. consectetur adipiscing elit. Sed iaculis nec erat vel fermentum. Suspendisse ullamcorper orci id turpis tempus placerat. Aliquam quis sem et augue consequat imperdiet venenatis a ipsum. Nulla tempor. lorem quis interdum ullamcorper. ex purus feugiat mi. sit amet consequat felis orci at urna. Donec accumsan maximus risus sit amet molestie. Quisque nec interdum sapien. eu tincidunt neque. Nam eget velit a nisi dignissim gravida vel id libero. Donec fermentum viverra ex sit amet venenatis. Cras tristique sed enim non hendrerit.
    </p>
</div>

---

## Ênfase - Strong & Em
```html
<p>
    Lorem <strong> ipsum </strong> <em> dolor </em> sit amet. consectetur adipiscing elit. Sed iaculis nec erat vel fermentum. Suspendisse ullamcorper orci id turpis tempus placerat. Aliquam quis sem et augue consequat imperdiet venenatis a ipsum. 
</p>
```

### Exemplo - Ênfase
<div>
    <p>
        Lorem <strong> ipsum </strong> <em> dolor </em> sit amet. consectetur adipiscing elit. Sed iaculis nec erat vel fermentum. Suspendisse ullamcorper orci id turpis tempus placerat. Aliquam quis sem et augue consequat imperdiet venenatis a ipsum. 
    </p>
</div>

---

## Quebra de linha - br
```html
<p>
    Lorem ipsum dolor sit amet. consectetur adipiscing elit. <br> Sed iaculis nec erat vel fermentum. Suspendisse ullamcorper orci id turpis tempus placerat. Aliquam quis sem et augue consequat imperdiet venenatis a ipsum. 
</p>
```

### Exemplo - Quebra de linha
<div>
    <p>
        Lorem ipsum dolor sit amet. consectetur adipiscing elit. <br> Sed iaculis nec erat vel fermentum. Suspendisse ullamcorper orci id turpis tempus placerat. Aliquam quis sem et augue consequat imperdiet venenatis a ipsum. 
    </p>
</div>

---

## Âncoras - a
    
A âncora ver acompanhada de um atributo( **href** ) e um valor( **Url** ).

    href - Endereço do hiperlink.

```html
<a href="https://www.google.com.br"> link da google </a>
```

### Exemplo - Âncoras
<div>
    <a href="https://www.google.com.br"> link da google </a>
</div>

---

A âncora pode utilizar o atributo **target** com o valor **_blank** para abrir em uma nova aba
```html
<a href="https://www.google.com.br" target="_blank"> link da google </a>
```

### Exemplo - Âncoras com a propriedade target="_blank"
<div>
    <a href="https://www.google.com.br" target="_blank"> link da google </a>
</div>

---

## Imagem - img

A imagem vem acompanhada de dois atributos e dois valores.

    src - Endereço do recurso
    alt - Um texto alternativo é utilizado para substituir uma imagem. quando a imagem não puder ser vista e tambem é interpretados pelos leitores de tela.

```html
<img src="https://github.com/mateusvilione/monitoria-HTML5-CSS3/blob/master/Monitoria/1%C2%B0%20Ciclo/Aula1/img/HTML_Logo.png" alt="Logo do html5">
```

### Exemplo - Imagem funcionando 
<div>
    <img src="https://github.com/mateusvilione/monitoria-HTML5-CSS3/blob/master/Monitoria/1%C2%B0%20Ciclo/Aula1/img/HTML_Logo.png" alt="Logo do html5">
</div>

### Exemplo - imagem não exibida
<div>
    <img src="https://github.com/mateusvilione/monitoria-HTML5-CSS3/blob/master/Monitoria/1%C2%B0%20Ciclo/Aula1/img/HTML.png" alt="Logo do html5">
</div>