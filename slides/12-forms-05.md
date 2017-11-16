### `<input>` atributos

- **value**: especifica un valor por defecto.
- **readonly**: el campo es de solo lectura, es decir, el valor no puede ser modificado.
- **disabled**: el campo no es clickable, no es modificable y no se enviará en el formulario.
- **size**: especifica el tamaño en caracteres del campo.

````HTML
<form action="/action_page.php">
  First name: <input type="text" name="fname" 
                     value="Mickey" size="40" 
                     readonly><br>
  Last name: <input type="text" name="lname" 
                    value="Mouse" disabled><br>
</form>
````


<form action="/action_page.php">
  First name: <input type="text" name="firstname" value="Mickey" readonly size="40"><br>
  Last name: <input type="text" name="lastname" value="Mouse" disabled><br>
</form>