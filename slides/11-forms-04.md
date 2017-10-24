### `<label>`

- Representa el título de un _input_.  
- Al clickar sobre él, pone el foco en el input correspondiente.  
- El atributo _for_ del label se debe corresponder con el _id_ del _input_ para relacionarlos.

````HTML
<form action="/action_page.php" method="post">
    <label for="user">Usuario:</label>
    <input type="text" id="user" name="user"> <br/>
    <label for="pass">Contraseña:</label>
    <input type="password" id="pass" name="pass"> <br/> 
    <input type="button" value="Entrar">
</form>
````

<form>
    <label for="user">Usuario:</label>
    <input type="text" id="user" name="user"> <br/>
    <label for="pass">Contraseña:</label>
    <input type="password" id="pass" name="pass"> <br/> 
    <input type="button" value="Entrar">
</form>
