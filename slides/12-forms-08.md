### `<input>` Checkbox

- Permite al usuario seleccionar CERO o MÁS opciones.
- Todas las opciones deben llevar distintos _name_.
- El valor enviado será el que se especifica en el atributo _value_.
- Las opciones seleccionadas por defecto se especifican con el atributo _checked_.

````HTML
<form>
  <input type="checkbox" name="vehicle1" 
         value="Bike" checked> I have a bike<br>
  <input type="checkbox" name="vehicle2" 
         value="Car" checked> I have a car 
</form>
````

<form>
  <input type="checkbox" name="vehicle1" value="Bike" checked> I have a bike<br>
  <input type="checkbox" name="vehicle2" value="Car" checked> I have a car 
</form>