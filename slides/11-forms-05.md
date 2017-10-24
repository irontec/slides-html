### `<select>`

Presenta un desplegable con un abanico de opciones.  
El atributo _selected_ indica la opción seleccionada por defecto.  
El valor que se enviará será el especificado en el atributo _value_.

````HTML
<label for="language">Select your language:</label>
<select id="language" name="language">
    <option value="1"> English </option>
    <option value="2"> Basque </option>
    <option value="3" selected> Spanish </option>
    <option value="4"> French </option>
</select>
````

<label for="language">Select your language</label>
<select id="language" name="languager">
    <option value="1"> English </option>
    <option value="2"> Basque </option>
    <option value="3" selected> Spanish </option>
    <option value="4"> French </option>
</select>