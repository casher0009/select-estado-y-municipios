# select-estado-y-municipios
Select de html y materializecss para selecciona estados y cargar sus municipios

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Mvochoa</title>

    <link href="http://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.97.7/css/materialize.min.css">
</head>
<body>
    <form action="" class="row">
        <div class="input-field col s12 m12 l6">
            <select id="estado" name="estado"></select>
            <label for="estado">Estado</label>
        </div>
        <div id="municipios" class="input-field col s12 m12 l6">
            <select id="municipio" name="municipio"></select>
            <label for="municipio">Municipio</label>
        </div>
    </form>

    <script type="text/javascript" src="https://code.jquery.com/jquery-2.1.1.min.js"></script>
    <script type="text/javascript" src="js/municipios.js"></script>
    <script type="text/javascript" src="js/select_estados.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.97.7/js/materialize.min.js"></script>
    <script type="text/javascript">
        $(document).ready(function(){
          $('select').material_select();
        });
    </script>
</body>
</html
```
