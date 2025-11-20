<!DOCTYPE html>
<html lang="es">
	<head>
		<meta charset="UTF-8">
		<title>Hotel Star Wars</title>	
		<style>
@font-face
	{
	font-family:'Star Jedi'
	src: url("StarJedi-DGRW.ttf") format("truetype");
	font-weight: normal;
	font-style: normal;
	}
h1
	{
	text-align: center;
	font-family: 'Star Jedi';
	font-size: 36px;
	}
h2 
	{
	text-align: center;
	font-family:'Star Jedi';
	font-size: 30px;
	text-decoration: underline;
	}
h3
	{
	text-align: center;
	font-family:Garamond;
	font-size: 23px;
	}
p
	{
	text-align: center;
	font-family:Garamond;
	font-size: 23px;
	}
form
	{
	text-align: center;
	font-family:'Star Jedi';
	font-size: 20px;
	}
option 
	{
	text-align: center;
	font-family:'Star Jedi';
	color: red;
	}
input
	{
	text-align: center;
	font-family:'Star Jedi';
	font-size: 18px;
	color: darkblue;
	}
textarea
	{
	resize: both;
	width: 50%;
	height: 100px;
	}
body
	{
	position: relative;
	background-color: #FFFFFF;			
	}
body::before
	{
	content: '';
	background-position: center;
	position: absolute;
	top: -80px;
	left: 0;
	width: 100%;
	height: 100%;
	background-image: url(https://upload.wikimedia.org/wikipedia/commons/f/f0/Batuu_%2852934802408%29.jpg);
	background-repeat: no-repeat;
	height: 1500px;
	background-size: cover;
	opacity: 0.2; 
	z-index: -1;
	}
</style>
	</head>
	<body>
		<h1>hotel star wars</h1>
		<h2>El mejor hotel de la galaxia</h2>
			<h3>Por favor, introduzca los siguientes datos para poder confirmar su reserva</h3>
			<h2>datos personales</h2>
		<form method="get">
			<label>Nombre&nbsp;&nbsp;&nbsp;&nbsp;</label>&nbsp;&nbsp; <input name="nombre" required>
			<br><br>
			<label>Apellidos&nbsp;&nbsp;&nbsp;&nbsp;</label>&nbsp;&nbsp; 	<input name="apellido" required>
			<br><br>
			<label>Teléfono de contacto&nbsp;&nbsp;&nbsp;&nbsp;</label>&nbsp;&nbsp; <input name="telefono" required>
			<br><br>
			<label>E-mail&nbsp;&nbsp;&nbsp;&nbsp;</label>&nbsp;&nbsp; <input name="email" required>
			<br><br>
			<label>Número de noches&nbsp;&nbsp;&nbsp;&nbsp;</label>&nbsp;&nbsp; 	<input name="numnoches" required>
			<br>
			<h2>fecha de llegada</h2>
			<p>Por favor, indique el día de llegada:
			<select name="Día de entrada">				
			    <option value="1">1</option>
			    <option value="2">2</option>
			    <option value="3">3</option>
			    <option value="4">4</option>
			    <option value="5">5</option>
			    <option value="6">6</option>
			    <option value="7">7</option>
			    <option value="8">8</option>
			    <option value="9">9</option>
			    <option value="10">10</option>
			    <option value="11">11</option>
			    <option value="12">12</option>
			    <option value="13">13</option>
			    <option value="14">14</option>
			    <option value="15">15</option>
			    <option value="16">16</option>
			    <option value="17">17</option>
			    <option value="18">18</option>
			    <option value="19">19</option>
			    <option value="20">20</option>
			    <option value="21">21</option>
			    <option value="22">22</option>
			    <option value="23">23</option>
			    <option value="24">24</option>
			    <option value="25">25</option>
			    <option value="26">26</option>
			    <option value="27">27</option>
			    <option value="28">28</option>
			    <option value="29">29</option>
			    <option value="30">30</option>
			    <option value="31">31</option>
			</select>			
			</p>			
			<p>Por favor, indique el mes:			
			<select name="Mes de entrada">
			    <option value="Enero">Enero</option>
			    <option value="Febrero">Febrero</option>
			    <option value="Marzo">Marzo</option>
			    <option value="Abril">Abril</option>
			    <option value="Mayo">Mayo</option>
			    <option value="Junio">Junio</option>
			    <option value="Julio">Julio</option>
			    <option value="Agosto">Agosto</option>
			    <option value="Septiembre">Septiembre</option>
			    <option value="Octubre">Octubre</option>
			    <option value="Noviembre">Noviembre</option>
			    <option value="Diciembre">Diciembre</option>
			</select>						
			</p>
			<h2>tipo de habitación</h2>
			<p>Por favor, indique el tipo de habitación que desea:
			<br><br>
			<input type="radio" name="habitacion" value="simple">Simple
			<input type="radio" name="habitacion" value="doble">Doble
			<input type="radio" name="habitacion" value="matrimonio">Matrimonio
			</p>			
			<h2>extras</h2>	
			<p><strong>Por favor, indique si desea alguna de las siguientes opciones adicionales:</strong>
			<br><br>
        	        <input type="checkbox" name="extras"> Desayuno
                	<input type="checkbox" name="extras">Comida
                	<input type="checkbox" name="extras">Cena
                	<input type="checkbox" name="extras">Cama supletoria
                	</p>			
			<h2>comentarios adicionales
			<br><br>
			<textarea name="area"></textarea> 
			</h2>
			<p>		
			<input type="submit" name="submit" onclick="alert('RESERVA REALIZADA - QUE LA FUERZA TE ACOMPAÑE');">&nbsp;&nbsp;
			<input type="reset" name="Reset" onclick="alert('FORMULARIO LIMPIO');">
			</p>	
		</form>
	</body>
</html>
