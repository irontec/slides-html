### `<input>` atributos

- **placeholder**: es una ayuda del valor que debe ir en el campo. Nos permite introducir un ejemplo o incluso prescindir del label.
- **required**: el campo es requerido.
- **autocomplete**: (des)activa el autocomplete del navegador.

````HTML
<form action="/action.php" autocomplete="on">
  <input type="text" autocomplete="off" 
         name="fname" placeholder="First name">
  <br>
  Last name: <input type="text" name="lname" 
                    placeholder="Mouse"><br>
</form>
````


<form action="/action_page.php" autocomplete="on">
  <input type="text" name="fname" placeholder="First name"
            autocomplete="off"><br>
  Last name: <input type="text" name="lname" 
                    placeholder="Mouse"><br>
</form>