# Forms

## HTML - 5 Forms

#### Só é enviado os valores que estão na tag &lt;form&gt;

```html
<form>
</form>
```

#### Tag input para receber dados

```html
<input>
```

<!--<input>-->


#### Associar o texto a caixa

```html
Nome: <input>
```

<!--Nome: <input>-->

#### Usar a label para focar na caixa ao ser clicada

```html
<label>
    Nome: <input>
</label>
```

<!--<label>-->
<!--    Nome: <input>-->
<!--</label>-->

### Tipo do input

#### Texto
```html
<label>
    Nome: <input type="text">
</label>
```

<!--<label>-->
<!--    Nome: <input type="text">-->
<!--</label>-->

#### Nome para resgatar a informação via JavaScript

```html
<label>
    Nome: <input type="text" name="nome">
</label>
```

<!--<label>-->
<!--    Nome: <input type="text" name="nome">-->
<!--</label>-->

#### Tamanho da caixa

```html
<label>
    Nome: <input type="text" name="nome" size="40">
</label>
```

<!--<label>-->
<!--    Nome: <input type="text" name="nome" size="40">-->
<!--</label>-->

#### Tamanho máximo do texto digitado

```html
<label>
    Nome: <input type="text" name="nome" size="40" maxlength="15">
</label>
```

<!--<label>-->
<!--    Nome: <input type="text" name="nome" size="40" maxlength="15">-->
<!--</label>-->

#### Id para manipular a tag por JavaScript e/ou CSS

```html
<label>
    Nome: <input type="text" name="nome" size="40" maxlength="15" id="nome">
</label>
```

##### Manipulação por css
```css
input#nome { width: 100px;}
```

<!--<label>-->
<!--    Nome: <input type="text" name="nome" size="40" maxlength="15" id="nome" style=" width: 500px; ">-->
<!--</label>-->

#### Area de texto. name. id

```html
<textarea name="comentarios" id="comentarios">
                        
</textarea>
```

<!--<textarea name="comentarios" id="comentarios">-->
                        
<!--</textarea>-->

#### Tamanho de linhas e colunas (Rows & cols)

```html
<textarea name="comentarios" id="comentarios" rows="15" cols="100">
                        
</textarea>
```

<!--<textarea name="comentarios" id="comentarios" rows="15" cols="100">-->
                        
<!--</textarea>-->

#### Caixa de seleção

```html
<select>
                    
</select>
```

<!--<select>-->
                    
<!--</select>-->

#### Opções da caixa de seleção

```html
<select>
    <option>Selecione...</option>
    <option>Item 1</option>
    <option>Item 2</option>
    <option>Item 3</option>
    <option>Item 4</option>
    <option>Item 5</option>
    <option>Item 6</option>
</select>
```

<!--<select>-->
<!--    <option>Selecione...</option>-->
<!--    <option>Item 1</option>-->
<!--    <option>Item 2</option>-->
<!--    <option>Item 3</option>-->
<!--    <option>Item 4</option>-->
<!--    <option>Item 5</option>-->
<!--    <option>Item 6</option>-->
<!--</select>-->

#### Value para usar no Js para saber qual foi o item selecionado

```html
<select>
    <option value="">Selecione...</option>
    <option value="item1">Item 1</option>
    <option value="item2">Item 2</option>
    <option value="item3">Item 3</option>
    <option value="item4">Item 4</option>
    <option value="item5">Item 5</option>
    <option value="item6">Item 6</option>
</select>
```

<!--<select>-->
<!--    <option value="">Selecione...</option>-->
<!--    <option value="item1">Item 1</option>-->
<!--    <option value="item2">Item 2</option>-->
<!--    <option value="item3">Item 3</option>-->
<!--    <option value="item4">Item 4</option>-->
<!--    <option value="item5">Item 5</option>-->
<!--    <option value="item6">Item 6</option>-->
<!--</select>-->

#### Selected marca valor default

```html
<select>
    <option value="">Selecione...</option>
    <option value="item1" selected>Item 1</option>
    <option value="item2">Item 2</option>
    <option value="item3">Item 3</option>
    <option value="item4">Item 4</option>
    <option value="item5">Item 5</option>
    <option value="item6">Item 6</option>
</select>
```

<!--<select>-->
<!--    <option value="">Selecione...</option>-->
<!--    <option value="item1" selected>Item 1</option>-->
<!--    <option value="item2">Item 2</option>-->
<!--    <option value="item3">Item 3</option>-->
<!--    <option value="item4">Item 4</option>-->
<!--    <option value="item5">Item 5</option>-->
<!--    <option value="item6">Item 6</option>-->
<!--</select>-->


#### Quantidade de linhas exibidas

```html
<select size="4"> <!-- quatro linhas de exibição -->
    <option value="">Selecione...</option>
    <option value="item1" selected>Item 1</option>
    <option value="item2">Item 2</option>
    <option value="item3">Item 3</option>
    <option value="item4">Item 4</option>
    <option value="item5">Item 5</option>
    <option value="item6">Item 6</option>
</select>
```

<!--<select size="4"> <!-- quatro linhas de exibição -->
<!--    <option value="">Selecione...</option>-->
<!--    <option value="item1" selected>Item 1</option>-->
<!--    <option value="item2">Item 2</option>-->
<!--    <option value="item3">Item 3</option>-->
<!--    <option value="item4">Item 4</option>-->
<!--    <option value="item5">Item 5</option>-->
<!--    <option value="item6">Item 6</option>-->
<!--</select>-->

#### Seleção multipla. utilizar a tecla Ctrl

```html
<select size="4" multiple> <!-- multipla seleção -->
    <option value="">Selecione...</option>
    <option value="item1" selected>Item 1</option>
    <option value="item2">Item 2</option>
    <option value="item3">Item 3</option>
    <option value="item4">Item 4</option>
    <option value="item5">Item 5</option>
    <option value="item6">Item 6</option>
</select>
```

<!--<select size="4" multiple> <!-- multipla seleção -->
<!--    <option value="">Selecione...</option>-->
<!--    <option value="item1" selected>Item 1</option>-->
<!--    <option value="item2">Item 2</option>-->
<!--    <option value="item3">Item 3</option>-->
<!--    <option value="item4">Item 4</option>-->
<!--    <option value="item5">Item 5</option>-->
<!--    <option value="item6">Item 6</option>-->
<!--</select>-->

#### Fieldset & Legend

```html
<fieldset>
    <legend>Legenda</legend>
</fieldset>
```

<!--<fieldset>-->
<!--    <legend>Legenda</legend>-->
<!--</fieldset>-->

#### Botões de rádio (radio buttons). name iguais e values diferentes. id diferentes

```html
<label>
    <input type="radio" name="valores" value="v1" id="valores-sim"> Sim
</label>

<label>
    <input type="radio" name="valores" value="v2" id="valores-não"> Não
</label>
```

<!--<label>-->
<!--    <input type="radio" name="valores" value="v1" id="valores-sim"> Sim-->
<!--</label>-->

<!--<label>-->
<!--    <input type="radio" name="valores" value="v2" id="valores-não"> Não-->
<!--</label>-->

#### Caixa de seleção (checkbox)

```html
<fieldset>
    <legend>Legenda</legend>
    <label>
        <input type="checkbox" name="valores" id="valores-1"> Item 1
    </label>

    <label>
        <input type="checkbox" name="valores" id="valores-2"> Item 2
    </label>
    
    <label>
        <input type="checkbox" name="valores" id="valores-3"> Item 3
    </label>
    
    <label>
        <input type="checkbox" name="valores" id="valores-4"> Item 4
    </label>
</fieldset>
```

<!--<fieldset>-->
<!--    <legend>Legenda</legend>-->
<!--    <label>-->
<!--        <input type="checkbox" name="valores" id="valores-1"> Item 1-->
<!--    </label>-->
<!--    <label>-->
<!--        <input type="checkbox" name="valores" id="valores-2"> Item 2-->
<!--    </label>-->
<!--    <label>-->
<!--        <input type="checkbox" name="valores" id="valores-3"> Item 3-->
<!--    </label>-->
<!--    <label>-->
<!--        <input type="checkbox" name="valores" id="valores-4"> Item 4-->
<!--    </label>-->
<!--</fieldset>-->

#### Enviar formulário

```html
<input type="submit" value="Enviar formulário">
```

<!--<input type="submit" value="Enviar formulário">-->

#### Reset limpa o form. mas pode dar problema pro usuario

```html
<input type="reset">
```

<!--<input type="reset">-->

### Envio de form (GET)

```html
<form method="get" >
```

### Exemplo de URL

    https://exemploDeUrl/PPSI-I/
    ?nome=oi&
    comentarios=oi&
    curso=ADS&
    informes=s&
    informes=informes-1&
    informes=informes-4

### Envio de form (POST) pegar dados (GET)

```html
<form method="post">
<form method="get">
```

### Action
```html
<form method="post" action="script/form.php">
```