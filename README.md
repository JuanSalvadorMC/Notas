
# Notas

## Comandos

### Captura de pantalla en Windows
```bash
Windows + Shift + S
```

### CSS

```bash
display: block;
```
 /* Ocultar elemento */
```bash
visibility: hidden;   /* Ocultar elemento */
```
```bash
<br/>         /*  salto de línea */
```
```bash
<hr>            línea		
```
```bash
<strong>        texto en negritas
```
```bash
<em>            texto en cursivas
```
```bash
<i>      itálica (medio cursiva)
```
```bash
<b>    negritas
```<u>…</u>subrayado
<span >         maquetación
<blockquote>    cita texto centrado

<ol>   + <li> lista numerada 
<ul>  +  <li> lista NO numerada
border: 2px solid  rgb(8, 177, 154); 

~/

<img src="direccion" alt="sub título" title="padrino" 
width="" height="200px"> imagenes

<a href="https://www.google.com/" target="_blank" title="link machin"> Link</a>  /* abrir en nueva ventana */

<span></span> /* etiqueta sin propiedad */

<blockquote></blockquote> /* cita de texto */
multiplicar td*3

multiplicador con varias etiquetas tr*2>td*3

tabla 
<table  border="1"  >
        <tr>
         <th>Nombre</th>
         <td>Apellido</td>
         <th>País</th>
          
          <tr>
              <td>Juan</td>
              <td colspan="2">Martínez</td>	
          </tr>
</table>

poner un link 
<a href="C:/Users/Salvador/Desktop/HTML/eje4.html" target="_blank">Contacto</a>

overflow-y: hidden; /* borrar scroll */

&nsbp; 

/* aplica para todo */
*{}

float:none /* sin reglas */

.titulo{
  color: white;
  margin: 80px auto 80px auto;
  font-size: 40px;
  text-shadow: 2px 2px 17px #117A65 ;
  border-radius: 16px;
  text-align: center;
}

color: #F2F3F4; /* color letra */
box-shadow: 2px 2px 17px 12px #117A65 ;
height: 600px;
font-weight: bold;
font-family: Helvetica;
```

### Angular

```bash
slc -- limpiar consola
ng new newapp
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
```

### JavaScript

```bash
<script>
</script>

<script type="text/javascript" src="/ruta">
</script>

alert("alerta navegador sencilla");

'use strict'

let ////vive solo en el bloque(llaves) donde es declarada
var /// vive en todo el código
const // no puede ser modificada

Number(X); /* transforma números string a enteros */
parseInt(X); /* transforma números string a enteros */
parseFloat(X); /* transforma números decimal string a decimal */
String(X); /* transforma números a string */
.toString(); /* transforma números a string */

debugger; /* cap.27 bucle for master JavaScript */

typeof // ver el tipo de dato
isNaN(numero1) // devuelve true o false si la var es diferente de int

var texto = "hola";
var numero = "23435";

/* guardar en local storage */
localStorage.setItem("usuarioBase", validar); 
usuarioBase = localStorage.getItem("usuarioBase");

console.log(texto.toString());
console.log(texto.toLowerCase());
console.log(texto.toUpperCase());

console.log(texto.length); /* calcular longitud */
console.log(texto.concat(numero)); /* concatenar */

/* Arrays */
lenguajes.sort(); /* muestra por orden alfabético */
lenguajes.reverse(); /* muestra al revés */

heroes.length == 0 &&
```

### Otros comandos y atajos

```bash
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
Mayús + Alt + Flecha abajo / Flecha arriba: Copiar línea arriba / abajo
Ctrl + Mayús + K: Eliminar línea
Ctrl + Fin: Ir al final del archivo
Ctrl + Inicio: Ir al principio del archivo
Alt + PgUp / PgDn: Desplazarse pantalla arriba / abajo
Ctrl + Mayús + Tabulador: Navegar por el historial de archivos editados
Alt + Flecha izquierda / Flecha derecha: Retroceder / avanzar en líneas editadas
Ctrl + Shift + S: Save As...
Ctrl + K, S: Save All
Shift + Alt + A: Comentar
Ctrl + Shift + P: Opciones
Lista de atajos de teclado: Ctrl + K + S
Shift + Alt arriba / abajo: Copiar línea 
Ctrl + L: Selecciona toda la línea
Ctrl + Alt + Clic: Multi cursores
Ctrl + D: Multicursor
```

### GIT

```bash
git pull  /* actualiza repositorio local */
git checkout  /* verifica la rama en la que te encuentras */

git clone https://gitlab.colaboracionsimba.net/captacion/sistemas-centrales-captacion/portalplataformacampanias/bdplataformacampanias.git

git branch -a /* ver ramas existentes */

git checkout LEACAP-384_integracion_bd /* cambio de rama */

git status /* ver cambios */

git add . /* agregar todos los cambios */

git add PAQUETES/20220726_PAALTACAMPANIAS.TXT /* agregar solo un cambio */

git commit -m 'LEACAP-404 -se sube paquete marcaje prod' /* crear commit */

git reset --soft HEAD~1 /* revertir commit */

git push /* subir cambio */
```

---
