# html
# VS-Code
- alt + z
- ctrl + k + c
- ctrl + k + u
- ctrl + a
- ctrl + b
# Emmet zencode
- html</br>
(.imgGeral.posLogo>caixa)+#container>(.menu>ul>(li>a[#]{menu-$})*5)+.baner+(.produtos>h3{produtos}+(.box>.imgProd.posProd-$.caixa+h6{Nome Produto - $}+p{R-$,00})*4)+(.servicos>h3{servicos}+(.box>h3{titulo-$}+.imgGeral.posServ-$.caixa+p>lorem30)*2)+.rodape>(p>lorem5)+ul>(li.imgGeral.posRede-$.caixa>a)*3

#container>(header>nav)+(main>article+aside)+footer</br>

form>(label>input[required]#nome)+(label>input[required]#endereco)+(label>input[required]#fone)+(label>input[required]#cep)+input:submit
</br>
- css</br>
https://docs.emmet.io/cheat-sheet/
```html
<!-- html5 identification -->
<!DOCTYPE html>
<!-- language identification -->
<html lang="en">
<!-- head of structure -->
<head>
    <!-- characters format -->
    <meta charset="UTF-8">
    <!-- run recent browser -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <!-- responsive -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- style css -->
    <link rel="stylesheet" href="css/global.css">
    <title>Document</title>
</head>
<body>
    <!-- estructure of website -->
</body>
</html>
```
```html
<!-- Unordination list -->
    <ul>
        <li>text1</li>
        <li>text2</li>
    </ul>
```
```html
<!-- Ordination list -->
    <ol>
        <li>text1</li>
        <li>text2</li>
    </ol>
```
```html
<!-- Tables -->
<table>
  <!-- Table row -->
  <tr>
    <!-- Table header -->
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <!-- Table data -->
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>
```

```html
    <!-- <form> Elements -->

<!-- Input -->
<input type="text" id="fname" name="fname">
<input type="submit" value="Submit">

<!-- Label -->
<label for="fname">First name:</label>

<!-- Select -->
<label for="cars">Choose a car:</label>
<select id="cars" name="cars">
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="fiat">Fiat</option>
  <option value="audi">Audi</option>
</select>

<!-- Textarea -->
<textarea name="message" rows="10" cols="30">
Hello World!
</textarea>

<!-- Button -->
<button type="button" onclick="alert('Hello World!')">Button</button>

<!-- Fieldset -->
<form action="/action_page.php">
  <fieldset>
    <legend>Personalia:</legend>
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname" value="John"><br>
    <label for="lname">Last name:</label><br>
    <input type="text" id="lname" name="lname" value="Doe"><br><br>
    <input type="submit" value="Submit">
  </fieldset>
</form>

<!-- Legend -->
<form action="/action_page.php">
  <fieldset>
    <legend>Personalia:</legend>
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname" value="John"><br>
    <label for="lname">Last name:</label><br>
    <input type="text" id="lname" name="lname" value="Doe"><br><br>
    <input type="submit" value="Submit">
  </fieldset>
</form>

<!-- Datalist -->
<form action="/action_page.php">
  <input list="browsers">
  <datalist id="browsers">
    <option value="Internet Explorer">
    <option value="Firefox">
    <option value="Chrome">
    <option value="Opera">
    <option value="Safari">
  </datalist>
</form>

<!-- Output -->
<form action="/action_page.php"
  oninput="x.value=parseInt(a.value)+parseInt(b.value)">
  0
  <input type="range"  id="a" name="a" value="50">
  100 +
  <input type="number" id="b" name="b" value="50">
  =
  <output name="x" for="a b"></output>
  <br><br>
  <input type="submit">
</form>

<!-- Option -->
<option value="Internet Explorer">

<!-- Optgroup -->
<select>
  <optgroup label="Grupo 1">
    <option>Opção 1.1</option>
  </optgroup>
  <optgroup label="Grupo 2">
    <option>Opção 2.1</option>
    <option>Opção 2.2</option>
  </optgroup>
</select>
```

https://www.w3schools.com/html/html_form_elements.asp

