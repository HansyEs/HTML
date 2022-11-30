# HTML
### Poner una toma de fotos en un formulario WEB en movil (user camara frontal y enviroment la trasera)
        <input type="file" capture="user" accept="image/*">
### Activar chequeo de ortografía en un campo
        <input type="text" spellcheck="true" lang="en">
### Indicar que ficheros se pueden subir en un input file
        <input type="file" accept=".jpeg,.png">
### Descargar algo que esté tras un enlace automáticamente
        <a href="image.png" download>
### Datalist permite añadir "sugerencias" a CUALQUIER input 
        <input list="my-list-values" id="my-list" name="my-list" type="text" />
        <datalist id="my-list-values">
            <option value="one">
            <option value="two">
            <option value="tree">
            <option value="four">
        </datalist>
