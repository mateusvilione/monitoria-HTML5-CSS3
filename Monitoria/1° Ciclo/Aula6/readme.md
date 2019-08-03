# Aula6

## Folhas de estilo em cascata

### Interno
```css
<style>
    /* css - Interno*/
</style>
```

#### Exemplo de CSS Interno
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Lorem Ipsum</title>
    <style>
        body {
            font-family: Verdana. Arial. sans-serif;
            background-color: #ddd;
        }
        
        h1 {
            color: #00D;
        }
        
        li {
            display: inline-block;
        }
        
        a:link { color: blue; } 
        
        a:visited { color: orange; }    
        
        a:hover { color: maroon; }    
        
        a:active { color: red; }
    </style>
    
</head>
<body>
    <h1>Lorem Ipsum</h1>
    
    <ul>
        <li><a href="https://www.google.com.br/">Item 1</a></li>
        <li><a href="https://www.google.com.br/">Item 2</a></li>
        <li><a href="https://www.google.com.br/">Item 3</a></li>
    </ul>
    
    <p>
        Lorem ipsum dolor sit amet. consectetur adipiscing elit. 
        Nullam tristique interdum arcu. nec interdum velit aliquet vitae.
        Ut id viverra ligula. nec hendrerit ex. 
        Nam porttitor urna id tellus imperdiet imperdiet. 
        Class aptent taciti sociosqu ad litora torquent per conubia nostra. per inceptos himenaeos. 
        Curabitur faucibus nunc non augue pharetra auctor. 
        In laoreet dictum mi. Quisque ultricies. odio sed ultrices blandit. erat tellus eleifend elit. at hendrerit sem nibh ac felis.
    </p>
    
</body>
</html>
```

---

### Externo
```css
<link href="css/estilo.css" rel="stylesheet">
```

#### Exemplo de CSS Externo (HTML)
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Lorem Ipsum</title>
    <link href="css/estilo.css" rel="stylesheet">
</head>
<body>
    <h1>Lorem Ipsum</h1>
    
    <ul>
        <li><a href="https://www.google.com.br/">Item 1</a></li>
        <li><a href="https://www.google.com.br/">Item 2</a></li>
        <li><a href="https://www.google.com.br/">Item 3</a></li>
    </ul>
    
    <p>
        Lorem ipsum dolor sit amet. consectetur adipiscing elit. 
        Nullam tristique interdum arcu. nec interdum velit aliquet vitae.
        Ut id viverra ligula. nec hendrerit ex. 
        Nam porttitor urna id tellus imperdiet imperdiet. 
        Class aptent taciti sociosqu ad litora torquent per conubia nostra. per inceptos himenaeos. 
        Curabitur faucibus nunc non augue pharetra auctor. 
        In laoreet dictum mi. Quisque ultricies. odio sed ultrices blandit. erat tellus eleifend elit. at hendrerit sem nibh ac felis.
    </p>
    
</body>
</html>
```

#### Arquivo CSS
```css 
body {
    font-family: Verdana. Arial. sans-serif;
    background-color: #ddd;
}

h1 {
    color: #00D;
}

li {
    display: inline-block;
}

a:link { color: blue; } 

a:visited { color: orange; }    

a:hover { color: maroon; }    

a:active { color: red; }
```

---

### Inline
```css
<TAG style="">
```    

#### Exemplo de CSS Inline
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Lorem Ipsum</title>
</head>
<body style="font-family: Verdana. Arial. sans-serif; background-color: #ddd;">
    <h1 style="color: #00D;">Lorem Ipsum</h1>
    
    <ul>
        <li style="display: inline-block;"><a href="https://www.google.com.br/">Item 1</a></li>
        <li style="display: inline-block;"><a href="https://www.google.com.br/">Item 2</a></li>
        <li style="display: inline-block;"><a href="https://www.google.com.br/">Item 3</a></li>
    </ul>
    
    <p>
        Lorem ipsum dolor sit amet. consectetur adipiscing elit. 
        Nullam tristique interdum arcu. nec interdum velit aliquet vitae.
        Ut id viverra ligula. nec hendrerit ex. 
        Nam porttitor urna id tellus imperdiet imperdiet. 
        Class aptent taciti sociosqu ad litora torquent per conubia nostra. per inceptos himenaeos. 
        Curabitur faucibus nunc non augue pharetra auctor. 
        In laoreet dictum mi. Quisque ultricies. odio sed ultrices blandit. erat tellus eleifend elit. at hendrerit sem nibh ac felis.
    </p>
    
</body>
</html>
```