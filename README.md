# Introducción---HTML-Visual-Studio-y-JavaScript

## Visual Studio Code.

Visual Studio Code (VS Code) es un editor de código desarrollado por Microsoft. Es gratuito, ligero y compatible con Windows, macOS y Linux. Está diseñado para programadores y ofrece herramientas avanzadas como:
- Autocompletar inteligente para facilitar la escritura de código.
- Resaltado de sintaxis parra mejorar la lectura y detección de errores.
- Live Server, una extesión que permite ver cambios en tiempo real en el navegador.

![imagen](Imagenes/imagen1.png)

## HTML

**HTML** (*HyperText Markup Language*) es el lenguaje de marcado utilizado para estructurar el contenido de una página web. Mediante diferentes etiqueas, permite definir encabezados, párrafos, imágenes, enlacees y formularios.

Cada documento **HTML** sigue una estructura básica que debe incluir ciertos elementos fundamentales para que el navegador lo interprete correctamente.

![imagen](Imagenes/imagen2.png)

## Generación rápida del estándar HTML en VS Code.

Para crear la estructura base de un documento **HTML** en **Visual Studio Code**, se puede utilizar un `atajo` muy útil:
1. Crea un archivo con la extensión .html (por ejemplo, `index.html`).
2. Escribe `!` y presiona **Enter** o **Tab**.
Esto generará automáticamente el siguiente código:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

</body>
</html>
```
Esto establece un documento **HTML5** con configuración de idioma, codificación de caractes y compatibilidad con dispositivos móviles.

## Introducción a JavaScript.

**JavaScript (JS)** es un lenguaje de programación que permite agregar interactividad y dinamismo a las páginas web. Mientras que **HTML** define la estructura y **CSS** el diseño, **JavaScript** permite:
- Manipular el DOM: Modificar el contenido de la página en tiempo real.
- Responder a eventos: Detectar clics, movimientos del mouse, teclas presionadas, etc.

![imagen](Imagenes/imagen3.png)

## Comparación entre JavaScript y C++

<table>
  <thead>
      <tr>
        <th>Característica</th>
        <th>JavaScript</th>
        <th>C++</th>
      </tr>
  </thead>
  <tbody>
      <tr>
        <td><b>Compilación</b></td>
        <td>Interpretado (no  necesita compilador)</td>
        <td>Compilado (requiere un compilador como g++)</td>
      </tr>
        <tr>
          <td><b>Tipado</b></td>
          <td>Dinámico (las variables cambian de tipo en ejecución)</td>
          <td>Estático(se define el tipo al declarar la varible)</td>
        </tr>
        <tr>
            <td><b>Uso principal</b></td>
            <td>Desarrolo web</td>
            <td>Aplicaciones y software de bajo nivel</td>
        </tr>
        <tr>
            <td><b>Lenguaje de nivel</b></td>
            <td>Alto nivel</td>
            <td>Medio - Alto (Depende de su uso)</td>
        </tr>
  </tbody>
</table>
## Vinculación de JavaScript en HTML

Para agregar *JavaScript* a un documento **HTML**, se recomienda hacerlo a través de un archivo externo.

```html
<body>
    <script type="module" src="main.js"></script>
</body>
```
- El script se ejecuta después de que se haya cargado todo el contenido *HTML*, evitando errores de refencia a elementos del *DOM*.
- No bloquea la carga de la página, lo que mejora el rendimiento.

Por defecto, los scripts en `JavaScript` se ejecutan en **modo clásico**, lo que puede generar problemas de organización en proyectos grandes. Para evitar esto, se usa `type="module"`, lo que permite:

- Importar y exportar funciones **entre archivos JavaScript**.
-Evitar conflictos de variables,**ya que cada módulo tiene su propio ámbito**.

## Video Tutorial.

Vinculación

<video src="Videos/Inicio.mp4" controls="">
