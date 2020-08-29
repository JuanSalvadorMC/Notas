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


Swal.fire(
  'Good job!',
  'You clicked the button!',
  'success'
)


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

///////ANGULAR
	ng serve --port 4201
ng c newcomponent --spec false

npm audit fix
eliminar carpeta node_modules

npm uninstall @angular-devkit/build-angular

npm install @angular-devkit/build-angular@0.13.0

///////////////////////////JAVASCRIPT
<script>
</script>

<script type="text/javascript" src="/ruta">
</script>


alert("alerta navegador sencilla");

modo estricto
'use strict'

let ////vive solo en el bloque(llaves) donde es declarada
var /// vive en todo el codigo
const // no puede ser modificada

Number(X);/  transforma numeros string a enteros
parseInt(X);/  transforma numeros string a enteros
parsefloat(X);/  transforma numeros decimal string a decimal
String(X); // transforma numeros a string 
.toString();// transforma numeros a string 

     debugger;// cap.27  bucle for master javascript

typeof// ver el tipo de dato
isNan(numero1)//devuelve un tru o false si la var es diferente de int

 //transformacion de textos

  var texto="hola";
  var nuemro="23435";


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

#wrapper {
  display: flex;
  align-items: center;
  justify-content: center;
}
