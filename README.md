# Notas
display :block;
visibility:hidden;   Ocultar elemento

<br/>           salto de linea
<hr>            linea		
<strong>        texto en negritas
<em>            texto en curcibas
<i>      italica (medio cursiba)
<b>    negritas
<u>…</u>subrayado
<span >         maquetacion
<blockquote>    cita texto centrado

<ol>   + <li> lista numerada 
<ul>  +  <li> lista NO numerada
border: 2px solid  rgb(8, 177, 154); 

~/

<img src="direccion" alt="sub titulo" title="padrino" 
width="" height="200px"> imagenes

    <a href="https://www.google.com/" target="_blank" title="link machin"> Link</a>//////abrir en nueva ventana

<span></span>/// etiqueta sin propiedade

<blockquote></blockquote>///cita de texto
multiplicar td*3

multimplicador con varias etiquetas tr*2>td*3

 tabla 
<table  border="1"  >
        <tr>
         <th>Nombre</th>
         <td>Apellido</td>
         <th>Pais</th>
          
          <tr>
              <td>Juan</td>
              <td colspan="2">Martinez</td>	
             
          </tr>
</table>


poner un links 
<a href="C:/Users/Salvador/Desktop/HTML/eje4.html" target="_blank">Contacto</a>

-----
CSS////////CSS////////CSS////////CSS////////////////CSS////////CSS////////CSS////////CSS////////CSS////////
------


borrrar scroll
overflow-y: hidden;


&nsbp; 

*{}//aplica para todo
float:none///sin reglas

propiedades
             .titulo{
              
              color: white;
margin: 80px auto 80px auto;
//width:400px;
font-size:40px;
text-shadow:2px 2px 17px #117A65 ;
border-radius: 16px;
text-align:center;
             }
color: #F2F3F4; clor letra
box-shadow:2px 2px 17px 12px #117A65 ;
height: 600px;
font-weight: bold;
font-family: Helvetica;
STREAMSERVE
P3_Aphe1L@@Qltr

salvador.martinez@ies-systems.com
Martinez2019

visibility:hidden
Swal.fire(
  'Good job!',
  'You clicked the button!',
  'success'
)
:nth-child(even){
  background-color: rgb(238, 238, 238);
}


////Selector general
*{

}

////Selector de etiqueta
h1 {

}

body footer h1 {

}

////Selector de id
#id{

}

////Selector de clase class
.class class1{

}
////Selector de atributo
#selector etiqueta {

}
input[type="text"]{
    margin: auto;
}

////Selectores hijos o por nivel solo se aplica a etiiquetas del nivel esepecificado
#selector ul> li> a {

}


dysplay: block;

*{
    font-style: italic;
    text-decoration: underline;
    font-weight: bolder;
  text-transform: uppercase;----> mayuscula
}

dashes= punteeado


CSS sigue un sitema similar a la programacion las lineas escritas al final de el codigo son las que definiran las propiedades finales

Importar fuentes descargadas
@font-face{
    src: ;
    font-family: ;
}
media query
@media screen and (min-width:600px){
    body{
     background: yellow;


    }
}

//////////////////////ANGULAR/////////////////////ANGULAR//////////////////////////ANGULAR/////////////////////////ANGULAR//////////////
slc-- limpiar consola
ng n newapp
--skipTests
ng serve --port 4201
ng serve -o
ng g c newcomponent-is --skipTests
ng g m modules
ng serve -c qa
ng serve --configuration=qa
	
npm audit fix
eliminar carpeta node_modules
npm uninstall @angular-devkit/build-angular
npm install @angular-devkit/build-angular@0.13.0


/////////////JAVASCRIPT//////////////JAVASCRIPT///////////////////JAVASCRIPT///////////////JAVASCRIPT//////////////JAVASCRIPT/////////////////////////////
<script>
</script>

<script type="text/javascript" src="/ruta">
</script>


alert("alerta navegador sencilla");

modo estricto
'use strict'

let ////vive solo en el bloque(llaves) donde es declarada
var /// vive en todo el codigo``
const // no puede ser modificada

Number(X);/  transforma numeros string a enteros
parseInt(X);/  transforma numeros string a enteros``
parseFloat(X);/  transforma numeros decimal string a decimal
String(X); // transforma numeros a string 
.toString();// transforma numeros a string 

     debugger;// cap.27  bucle for master javascript

typeof// ver el tipo de dato
isNan(numero1)//devuelve un tru o false si la var es diferente de int

 //transformacion de textos

  var texto="hola";
  var nuemro="23435";

	guardar en local storage
	localStorage.setItem("usuarioBase", validar); 
	usuarioBase=localStorage.getItem("usuarioBase");

console.log( texto.toString()    );
console.log( texto.toLowerCase()  );
console.log( texto.toUpperCase()  );
 //calcular longitud
console.log( texto.length );
 //concatenar
 console.log( texto.concat(nuemro));


//Arrays
lenguajes.sort();//muestra por orden alfabetico
lenguajes.reverse();//muestra al reves

heroes.length == 0 &&


Alineación vertical y horizontal.






 display: none;
    float: both;

float: left ---caja
.centrar{
  display: flex;
  align-items: center;
  justify-content: center;
}

<td class="col-3 box">    <img [src]="liq.imagenes" class="img-thumbnail" alt="Responsive"></td>

style="background-image:url('slide/ed-sheeran.jpg'">
Abrir archivo: CTRL + O
Abrir carpeta: CTRL + K + CTRL + O
Guardar archivo: CTRL + S
Crear un nuevo archivo: CTRL + N
Cerrar archivo abierto: CTRL + W
Cerrar archivos abiertos: CTRL + K, CTRL + W
Deshacer: CTRL + Z
Rehacer: CTRL + Y
Buscar en archivo abierto: CTRL + F
Buscar en archivos: CTRL + SHIFT + F
Reemplazar: CTRL + H
Seleccionar todo: CTRL + A
Pantalla completa: F11
Acercar Zoom: CTRL + +
Alejar Zoom: CTRL + –
Abrir paleta de comandos: CTRL + SHIFT + P
Abrir explorador de archivos: CTRL + SHIFT + E
Acceder a extensiones (instaladas y para instalar): CTRL + SHIFT + X
Debug: CTRL + SHIFT + D
Corte de palabras (Word Wrap): ALT + Z
Abrir terminal integrado: CTRL + Ñ
Ver/editar atajos de teclado: CTRL + K+ CTRL + S
Buscar archivo: Ctrl+p
Mayús + Alt + Flecha abajo / Flecha arriba	Copiar línea arriba / abajo
Ctrl + Mayús + K	Eliminar línea
Ctrl + Fin	Ir al final del archivo
Ctrl + Inicio	Ir al principio del archivo
Alt + PgUp / PgDn	Desplazarse pantalla arriba / abajo
Ctrl + Mayús + Tabulador	Navegar por el historial de archivos editados
Alt + Flecha izquierda / Flecha derecha	:Retroceder / avanzar en lineas editadas
Ctrl+Shift+S  :Save As...
Ctrl+K, S : Save All
SHift + Alt +A: comentar
Ctrl+ Shift+P opciones
lista de short cuts Ctrl +k+s
shift + Alt arriba / abajo copiar linea 
ctrl + l selecciona toda la linea
ctrl + alt + clic multi cursores
ctrl + d multicursor
^ nivel arriba
() agrupacion	
{}texto
$ incrementar
[] atributos 
---------------------------------------------------------------------
107.180.43.14

hf6ubely41u5
hf6ubely41u5
hf6ubely41u5

iesSystems*20
iesSystems*20
**
cd ~/app-node
pkill node
nohup node ./server/server.js & 

&nbsp; espacio
--------------------------------------------------------------------

 height: 100vh;

 position:absolute;
                top:50%;
                left:50%; aliniar horizontal
		
		
		
	  object-fit: cover;
  filter: brightness(80%);
  cursor: pointer;
  transition: 1s;	
		
		user-select: none;
		 cursor: pointer;
		
		
		
		//@ts-check
		
		
		position: fixed; /*Fixed ya que queremos que la posición sea en relación al navegador*/
top: 0; /*El valor 0 indica que va a quedar arriba de todo*/



nav {
position: fixed; /*Fixed ya que queremos que la posición sea en relación al navegador*/
top: 0; /*El valor 0 indica que va a quedar arriba de todo*/
left: 0; /*Para que el menu se ubique siempre en la parte izquierda de la pantalla*/
width: 100%; /*100% para que ocupe todo el ancho del navegador*/
}

VARIABLES CCS
:root {
--variabley:32 px:
@media screen and (min-width:770px){
--variabley:42 px:
}
}

font-size : var(--variabley);

--gColumns:repeat(4,1fr);
--gGap:4rem;

.grid{
display:grid;
grid-template-columns:vas(--gColumns);
grid-gap:var(--gGap);
}


position

static//default

realative // se mueve apartir de el contenedor en el que este
absolute// se ensimay pierde su espaci en la pantalla
fixed// se mueve partir de toda la pnatalla

disable estilos
------------------------------------------------
.btn-colorRe:disabled,
button[disabled]{
  background: #ffffff !important;
     border: 1px solid #999999;
     background-color: #cccccc;
     color: #666666 !important;
}
.btn-colorRe:disabled:hover,
button[disabled]{
  background: #ffffff !important;
     border: 1px solid #999999;
     background-color: #cccccc;
     color: #666666 !important;
}

:root {
  --azul: #1b3e69;
  --gris:rgb(190, 190, 190);
  --verde:#60b622;
}
	landscape horizontal
	portrait vertical

    @media screen and (orientation: portrait){

        .precios{
            width: 99%;
            border-radius: 2px;
        }
    }
console.log(`${porcentaje} = (${d.row(a)]/${opcional})`);
	
	
	ntlf become484
	
	
document.getElementById('searchd').value='que onda ya lo automatice 3';
setTimeout(()=>{

document.getElementById('search-icon-legacyd').click();
},2000)
		
CSS GRID **************************************************************
	  /* declaracion del tipo de Dispaly */
        display: grid;

        /* ordenar los items */
        justify-content: space-evenly;
        align-items: center;

        /* Dimenciones internas del item */
        justify-self: stretch;
        justify-self: stretch;
        /* delaracion de las columnas y filas */
        grid-template-columns: 1fr 300px minmax(100px, 2fr);
        grid-template-rows: repeat(100px, auto);
        grid-template-areas: "header 		header 		header"
						 "sidebar-1 	contenido 	sidebar-2"
						 "sidebar-1 	widgets 	sidebar-2"
						 "footer 		footer 		footer";

                         /* separar items */
        grid-gap: 20px;
        /* espacio de los items */
        grid-column: span 3;
        grid-column-start: sidebar -1;
        grid-column: sidebar -1;
        grid-column-end: header;
        grid-row: 1/4;
        /* sub grid para alinear contenido interno de los items */
        grid-template-rows: subgrid;
        grid-template-columns: subgrid;
        /* items implicitos o por default */
        grid-auto-rows: 400px;
        grid-auto-columns: 2fr;
        /* orden de los items */
        grid-auto-flow: row;
        /* Rellenar espacios */
        grid-auto-flow: dense;
        /* convinacion de formatos de flow */
        grid-auto-flow: column dense;
        /* auto fill equivalente a un grap */
        grid-template-columns: repeat(auto-fill,minmax(100px, 1fr));
        /*  auto fit equivalente a un grap pero con tamaños dinamicos de item*/
        grid-template-columns: repeat(auto-fit,minmax(100px, 1fr));
	
	
	
	
	/////////////////////////////////////////////////////////////////////// GIT  ////////////////////////////////////////////////////////////////////////////
	
	
	git pull  - actualiza repositorio local
	
	git checkout  - verifica la rama en la que te encuentras



 bajar un repo

 $ git clone https://gitlab.colaboracionsimba.net/captacion/sistemas-centrales-captacion/portalplataformacampanias/bdplataformacampanias.git


  git branch -a ver ramas existentes


 
cambio de rama
git checkout LEACAP-384_integracion_bd


ver cambios
git status

agregar todos los cambios
git add.

agregar  solo un cambio
git add  PAQUETES/20220726_PAALTACAMPANIAS.TXT

crear commit
git commit -m 'LEACAP-404 -se sube paquete marcaje prod'


revertir commit
git reset --soft HEAD~1

subir cambio
git push


