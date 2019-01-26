# Formulaire

Balise à étudier : 
* form
* input
* select
* textarea
* button

## form

Atttributs : 
* action="/action_page.php" 
* method="post" ou "get"
 
https://developer.mozilla.org/fr/docs/Web/HTML/Element/Form

## input

Deux attributs obligatoires : `name` et `type`

### Input Type Text

```html
<form>
  First name:<br>
  <input type="text" name="firstname"><br>
  Last name:<br>
  <input type="text" name="lastname">
</form>
```


### Input Type Password

```html
<form>
  User name:<br>
  <input type="text" name="username"><br>
  User password:<br>
  <input type="password" name="psw">
</form>
```

### Input Type Submit

```html
<form action="/action_page.php">
  First name:<br>
  <input type="text" name="firstname" value="Mickey"><br>
  Last name:<br>
  <input type="text" name="lastname" value="Mouse"><br><br>
  <input type="submit">
</form>
```

### Input Type Reset

```html
<form action="/action_page.php">
  First name:<br>
  <input type="text" name="firstname" value="Mickey"><br>
  Last name:<br>
  <input type="text" name="lastname" value="Mouse"><br><br>
  <input type="submit" value="Submit">
  <input type="reset">
</form>
```
 
### Input Type Radio

```html
<form>
  <input type="radio" name="gender" value="male" checked> Male<br>
  <input type="radio" name="gender" value="female"> Female<br>
  <input type="radio" name="gender" value="other"> Other
</form>
```

### Input Type Checkbox

```html
<form>
  <input type="checkbox" name="vehicle1" value="Bike"> I have a bike<br>
  <input type="checkbox" name="vehicle2" value="Car"> I have a car 
</form>
```

### Input Type Button

```html
<input type="button" onclick="alert('Hello World!')" value="Click Me!">
```

https://www.w3schools.com/html/html_form_input_types.asp

## select

```html
<select name="cars">
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="fiat">Fiat</option>
  <option value="audi">Audi</option>
</select>
```

https://developer.mozilla.org/fr/docs/Web/HTML/Element/select

## textarea

```
<textarea name="message" rows="10" cols="30">
The cat was playing in the garden.
</textarea>
```

https://developer.mozilla.org/fr/docs/Web/HTML/Element/Textarea

## button

```
<button type="button" onclick="alert('Hello World!')">Click Me!</button>
```

https://developer.mozilla.org/fr/docs/Web/HTML/Element/Button
