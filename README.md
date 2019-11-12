<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8" />
<title>FORMULARIO DE PRUEBA DE HTML5</title>
</head>
<body>
<body style="background-color: lightblue;" >
<h1 style= "color:purple;" ><center>FORMULARIO DE PRUEBA DE HTML5</center></h1>
<form action="." oninput="range_control_value.value = range_control.valueAsNumber">
<p>
Nombre: <input type="text" name="name_control" autofocus required />
<p>
Correo Electrónico: <input type="email" name="email_control" required />
<p>
URL: <input type="url" name="url_control" placeholder="Escripe la URL de tu página web personal" />
<p>
Fecha: <input type="date" name="date_control" />
<p>
Tiempo: <input type="time" name="time_control" />
<p>
Fecha y hora: <input type="datetime" name="datetime_control" />
<p>
Mes: <input type="month" name="month_control" />
<p>
Semana: <input type="week" name="week_control" />
<p>
Número (min -10, max 10): <input type="number" name="number_control" min="-10" max="10" value="0" />
<p>
Teléfono: <input type="tel" name="tel_control" />
<p>
Término de búsqueda: <input type="search" name="search_control" />
<p />
Color Favorito: <input type="color" name="color_control" />
<p/>
<input type="submit" value="Submit!" />
</p>
</form>
</body>
</html


