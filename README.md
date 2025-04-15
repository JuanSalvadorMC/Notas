# Notas / Comandos / codigos

### Comando Captura de pantalla en Windows

```bash
Windows + Shift + S
```

### CSS

```bash
display: block;  /* Ocupa todo el ancho disponible al 100% */
```

```bash
visibility: hidden;   /* Ocultar elemento */
```

```bash
:nth-child(even){
  background-color: rgb(238, 238, 238);
}
```

```bash
/* Selector general */
*{
}
```

#### Alineación vertical y horizontal.
```bash
.centrar {
  display: flex; /* Activa Flexbox */
  align-items: center;     /* Centra VERTICALMENTE */
  justify-content: center; /* Centra HORIZONTALMENTE */
}

```

```bash
input[type="text"]{
    margin: auto;
}
/*  Selectores hijos o por nivel solo se aplica a etiiquetas del nivel esepecificado  */
#selector ul> li> a {
}
dysplay: block;
*{
    font-style: italic;
    text-decoration: underline;
    font-weight: bolder;
  text-transform: uppercase;----> mayuscula
}
```

```bash
border: 2px solid  rgb(8, 177, 154);
```

```bash
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

```

```bash

overflow-y: hidden; /* borrar scroll */

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
height: 100vh;
git branch -a /* ver ramas existentes */
position:absolute;
git checkout LEACAP-384_integracion_bd /* cambio de rama */
top:50%;
left:50%; aliniar horizontal
```

```bash
object-fit: cover;
filter: brightness(80%);
cursor: pointer;
transition: 1s;
user-select: none;
cursor: pointer;
position: fixed; /*Fixed ya que queremos que la posición sea en re
lación al navegador*/
top: 0; /*El valor 0 indica que va a quedar arriba de todo*/
```
```bash
nav {
  position: fixed; /*Fixed ya que queremos que la posición sea en relación al navegador*/
  top: 0; /*El valor 0 indica que va a quedar arriba de todo*/
  left: 0; /*Para que el menu se ubique siempre en la parte izquierda de la pantalla*/
  width: 100%; /*100% para que ocupe todo el ancho del navegador*/
}
```
### 📌 POSITION EN CSS 📌
```bash
/* 1. position: static (Valor por defecto) */
.elemento-static {
  position: static; /* Sigue el flujo normal del documento */
  top: 20px; /* ⚠️ NO TIENE EFECTO (ignora top/right/bottom/left) */
}
/* Uso: Cuando quieres resetear la posición de un elemento */
```
```bash
/* 2. position: relative */
.elemento-relative {
  position: relative; /* Mantiene su espacio en el flujo */
  top: 20px; /* Se mueve 20px DESDE su posición original */
  left: 30px; /* (Relativo a sí mismo) */
  z-index: 1; /* 🎯 Permite controlar el apilamiento */
}
/* Uso: Ajustes finos de posición sin afectar otros elementos */
```
```bash
/* 3. position: absolute */
.elemento-absolute {
  position: absolute; /* Sale del flujo normal (no ocupa espacio) */
  top: 0; /* Se posiciona respecto al primer ancestro NO static */
  right: 0; /* Si no hay, usa el viewport (como fixed) */
  /* ⚠️ Necesita un contenedor con position: relative/absolute/fixed */
}
/* Uso: Menús desplegables, tooltips, elementos superpuestos */
```
```bash
/* 4. position: fixed */
.elemento-fixed {
  position: fixed; /* Sale del flujo y se fija en la pantalla */
  bottom: 20px; /* 20px desde el borde inferior del viewport */
  right: 20px; /* No se mueve al hacer scroll */
  /* 📱 Ideal para botones flotantes en móvil */
}
/* Uso: Chat de soporte, botones "volver arriba" */
```
```bash
/* 5. position: sticky (¡Faltaba en tu lista!) */
.elemento-sticky {
  position: sticky; /* Híbrido entre relative y fixed */
  top: 0; /* Se pega al borde cuando el scroll llega a su posición */
  /* 🧠 Necesita un contenedor con overflow: visible */
}
/* Uso: Cabeceras de tabla, menús que siguen al scroll */
```
```bash
/* 🚨 DISABLE ESTILOS (Corrección) */
.boton-deshabilitado:disabled,
.boton-deshabilitado[disabled] {
  opacity: 0.6; /* Transparencia para indicar estado */
  cursor: not-allowed; /* Cambia el cursor */
  /* 🛑 No usar 'disable estilos' (nombre incorrecto) */
  /* ✅ Correcto: :disabled o [disabled] */
}
```


```bash
.btn-colorRe:disabled,
button[disabled]{
  background: #ffffff !important;
     border: 1px solid #999999;
     background-color: #cccccc;
     color: #666666 !important;
}
```
```bash
.btn-colorRe:disabled:hover,
button[disabled]{
  background: #ffffff !important;
     border: 1px solid #999999;
     background-color: #cccccc;
     color: #666666 !important;
}
```
```bash
:root {
  --azul: #1b3e69;
  --gris:rgb(190, 190, 190);
  --verde:#60b622;
}
```
```bash
      orientation:  landscape horizontal
      orientation:  portrait vertical
    @media screen and (orientation: portrait){
       /* Codigo */
    }
    ```
```bash
    @media screen and (orientation: landscape){
       /* Codigo */
    }
    ```
```bash

    @media screen and (orientation: viewport){
       /* Codigo */
    }
         ```

```bash
## VARIABLES CCS

:root {
--variabley:32 px:
@media screen and (min-width:770px){
--variabley:42 px:
}
}
font-size : var(--variabley);


````

### CSS GRID
```bash
        --gColumns:repeat(4,1fr);

        --gGap:4rem;
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
        grid-template-areas: "
          header             header                 header"
          "sidebar-1         contenido         sidebar-2"
          "sidebar-1         widgets         sidebar-2"
          "footer                 footer                 footer";
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
        /* auto fill equivalente a un grap */
        grid-template-columns: repeat(auto-fill,minmax(100px, 1fr));
        /* auto fit equivalente a un grap pero con tamaños dinamicos de item*/
        grid-template-columns: repeat(auto-fit,minmax(100px, 1fr));
        /* auto fill equivalente a un grap */
```
```bash
        .grid{
display:grid;
grid-template-columns:vas(--gColumns);
grid-gap:var(--gGap);
}

```


### HTML5

```bash
&nsbp;        /*  espacio en blanco en html5 */
```

```bash
<br/>         /*  salto de línea */
```

```bash
<hr>            /*  línea		*/
```

```bash
<strong>      /*    texto en negritas*/
```

```bash
<em>             /* texto en cursivas*/
```

```bash
<i>     /*   itálica (medio cursiva)*/
```

```bash
<b>    negritas </b> /*  texto en negritas*/

```

```bash
<u>…</u>subrayado
```
```bash
<span >         maquetación
```
```bash
<blockquote>    cita texto centrado
```
```bash

<ol>   + <li> lista numerada
```
```bash
<ul>  +  <li> lista NO numerada
```
```bash
<td class="col-3 box">    <img [src]="liq.imagenes" class="img-thumbnail" alt="Responsive"></td>
style="background-image:url('slide/ed-sheeran.jpg'">
```
```bash
<img src="direccion" alt="sub título" title="padrino"
width="" height="200px"> imagenes
```
```bash
<a href="https://www.google.com/" target="_blank" title="link machin"> Link</a>  /* abrir en nueva ventana */
```
```bash
<span></span> /* etiqueta sin propiedad */
```
#### Cita de texto
```bash
<blockquote></blockquote> /* cita de texto */
```

#### Tabla
```bash
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
```

#### Adjuntar link
```bash
<a href="C:/Users/Salvador/Desktop/HTML/eje4.html" target="_blank">Contacto</a>
```

```bash
document.getElementById('searchd').value='que onda ya lo automatice 3';
```

```bash
setTimeout(()=>{
document.getElementById('search-icon-legacyd').click();
},2000);
```

### Angular

```bash
Swal.fire(
  'Good job!',
  'You clicked the button!',
  'success'
);
```

```bash
slc -- limpiar consola
```
```bash
ng new newapp --skipTests
```
```bash
ng serve --port 4201
```
```bash
ng serve -o
```
```bash
ng g c newcomponent-is --skipTests
```
```bash
ng g m modules
```
```bash
ng serve -c qa
```
```bash
ng serve --configuration=qa
```
```bash

```
```bash
npm audit fix
```
```bash
eliminar carpeta node_modules
```
```bash
npm uninstall @angular-devkit/build-angular
```
```bash
npm install @angular-devkit/build-angular@0.13.0
```

### JavaScript/ECMAScript

##### template string
```bash
console.log(`${porcentaje} = (${d.row(a)]/${opcional})`);
```

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

```

## VS Code & Snippet de Emmet 
```bash
multiplicar td*3

multiplicador con varias etiquetas tr*2>td*3

^ nivel arriba
() agrupacion
{}texto
$ incrementar
[] atributos

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


```

### GIT

```bash
git pull  /* actualiza repositorio local */

git checkout  /* verifica la rama en la que te encuentras */

git clone https://gitlab.colaboracionsimba.net/campanias/bdplataformacampanias.git

git branch -a /* ver ramas existentes */

git checkout LEACAP-384_integracion_bd /* cambio de rama */

git status /* ver cambios */

git add . /* agregar todos los cambios */

git add PAQUETES/20220726_PAALTACAMPANIAS.TXT /* agregar solo un cambio */

git commit -m 'LEACAP-404 -se sube paquete marcaje prod' /* crear commit */

git reset --soft HEAD~1 /* revertir commit */

git push /* subir cambio */

git status /* ver cambios */

git add . /* agregar todos los cambios */

git add PAQUETES/20220726_PAALTACAMPANIAS.TXT /* agregar solo un cambio */

git reset --soft HEAD~1 /* revertir commit */

git push /* subir cambio */

```

---
