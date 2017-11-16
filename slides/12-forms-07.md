### `<input>` Radio button

- Permite al usuario seleccionar UNA opción.
- Todas las opciones deben llevar el mismo _name_.
- El valor enviado será el que se especifica en el atributo _value_.
- La opción seleccionada por defecto se especifica con el atributo _checked_.

````HTML
<form>
  <input type="radio" name="gender" 
         value="male" checked> Male<br>
  <input type="radio" name="gender" 
         value="female"> Female<br>
  <input type="radio" name="gender" 
         value="other"> Other
</form>
````


<form>
  <input type="radio" name="gender" value="male" checked> Male<br>
  <input type="radio" name="gender" value="female"> Female<br>
  <input type="radio" name="gender" value="other"> Other
</form>