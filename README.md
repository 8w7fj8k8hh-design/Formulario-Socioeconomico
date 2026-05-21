<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Formulario Socioeconómico</title>

<style>

body{
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg,#36d1dc,#5b86e5);
    margin:0;
    padding:0;
}

.contenedor{
    width:85%;
    max-width:900px;
    background:white;
    margin:30px auto;
    padding:30px;
    border-radius:20px;
    box-shadow:0px 0px 20px rgba(0,0,0,0.3);
    animation: aparecer 1s ease;
}

@keyframes aparecer{
    from{
        opacity:0;
        transform:translateY(-20px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}

h1{
    text-align:center;
    color:#1565c0;
    font-size:40px;
}

h2{
    color:#1976d2;
    margin-top:35px;
    border-left:6px solid #1976d2;
    padding-left:10px;
}

.pregunta{
    background:#f2f2f2;
    padding:15px;
    margin-top:15px;
    border-radius:12px;
}

label{
    display:block;
    margin-top:8px;
    cursor:pointer;
}

input, select{
    width:100%;
    padding:10px;
    border-radius:10px;
    border:2px solid #ccc;
    margin-top:8px;
    box-sizing:border-box;
}

input[type="radio"],
input[type="checkbox"]{
    width:auto;
    margin-right:8px;
}

button{
    width:100%;
    padding:15px;
    background:#1565c0;
    color:white;
    border:none;
    border-radius:15px;
    font-size:20px;
    margin-top:35px;
    cursor:pointer;
    transition:0.3s;
}

button:hover{
    background:#0d47a1;
    transform:scale(1.03);
}

footer{
    text-align:center;
    margin-top:25px;
    color:gray;
}

</style>
</head>

<body>

<div class="contenedor">

<h1>Formulario Socioeconómico</h1>

<form>

<!-- DATOS GENERALES -->

<h2>Datos Generales</h2>

<div class="pregunta">
<label>Nombre completo:</label>
<input type="text" placeholder="Escribe tu nombre completo">
</div>

<div class="pregunta">
<label>Edad:</label>
<input type="number" placeholder="Escribe tu edad">
</div>

<div class="pregunta">
<label>Fecha de nacimiento:</label>
<input type="date">
</div>

<div class="pregunta">
<p>Sexo:</p>

<label>
<input type="radio" name="sexo"> Femenino
</label>

<label>
<input type="radio" name="sexo"> Masculino
</label>

<label>
<input type="radio" name="sexo"> Otro
</label>
</div>

<div class="pregunta">
<p>&#191;Con cuántas personas vives?</p>

<label>
<input type="radio" name="familia"> 1 a 3 personas
</label>

<label>
<input type="radio" name="familia"> 4 a 6 personas
</label>

<label>
<input type="radio" name="familia"> 7 o más
</label>
</div>

<!-- ESTUDIOS -->

<h2>Estudios</h2>

<div class="pregunta">
<label>Nombre del kinder:</label>
<input type="text" placeholder="Escribe el nombre del kinder">
</div>

<div class="pregunta">
<label>Nombre de la primaria:</label>
<input type="text" placeholder="Escribe el nombre de la primaria">
</div>

<div class="pregunta">
<label>Nombre de la secundaria:</label>
<input type="text" placeholder="Escribe el nombre de la secundaria">
</div>

<div class="pregunta">
<label>Nombre de la preparatoria:</label>
<input type="text" placeholder="Escribe el nombre de la preparatoria">
</div>

<div class="pregunta">
<p>&#191;Actualmente estudias?</p>

<label>
<input type="radio" name="estudia"> Sí
</label>

<label>
<input type="radio" name="estudia"> No
</label>
</div>

<!-- INFORMACIÓN DE LA CASA -->

<h2>Información de la Casa</h2>

<div class="pregunta">
<p>&#191;La casa cuenta con luz?</p>

<label>
<input type="radio" name="luz"> Sí
</label>

<label>
<input type="radio" name="luz"> No
</label>
</div>

<div class="pregunta">
<p>&#191;La casa tiene internet?</p>

<label>
<input type="radio" name="internet"> Sí
</label>

<label>
<input type="radio" name="internet"> No
</label>
</div>

<div class="pregunta">
<label>&#191;Cuántos cuartos tiene la casa?</label>
<input type="number">
</div>

<div class="pregunta">
<p>&#191;Qué servicios tiene la vivienda?</p>

<label>
<input type="checkbox"> Agua potable
</label>

<label>
<input type="checkbox"> Drenaje
</label>

<label>
<input type="checkbox"> Gas
</label>

<label>
<input type="checkbox"> Cable
</label>

<label>
<input type="checkbox"> Internet
</label>
</div>

<div class="pregunta">
<p>&#191;La vivienda es?</p>

<label>
<input type="radio" name="vivienda"> Propia
</label>

<label>
<input type="radio" name="vivienda"> Rentada
</label>

<label>
<input type="radio" name="vivienda"> Prestada
</label>
</div>

<!-- BOTÓN -->

<button type="submit">Enviar Formulario</button>

</form>

<footer>
Formulario realizado por ARIADNA ROSALES MORENO
</footer>

</div>

</body>
</html>
