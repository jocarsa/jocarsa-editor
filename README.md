# Jocarsa Editor

**Jocarsa Editor** es un editor visual HTML tipo WYSIWYG desarrollado en JavaScript puro y CSS puro.

Está pensado para ser ligero, fácil de integrar, fácil de comprender y utilizable directamente dentro de cualquier formulario HTML estándar. El editor transforma un `textarea` convencional en un editor visual manteniendo siempre sincronizado el contenido HTML original para que pueda enviarse al servidor sin necesidad de procesos adicionales.

Repositorio oficial: `https://github.com/jocarsa/jocarsa-editor`  
Demo pública: `https://jocarsa.github.io/jocarsa-editor/`

---

# ¿Qué es Jocarsa Editor?

Jocarsa Editor es una solución sencilla para quienes necesitan incorporar edición visual HTML en sus proyectos sin depender de librerías externas pesadas.

Su filosofía es:

- simplicidad
- independencia tecnológica
- facilidad de mantenimiento
- código completamente legible
- integración inmediata

Está especialmente orientado a:

- formularios web
- paneles de administración
- pequeños CMS
- plataformas educativas
- software empresarial
- herramientas internas

Todo el sistema está construido exclusivamente con tecnologías nativas del navegador.

---

# Tecnologías utilizadas

- JavaScript puro
- CSS puro
- HTML estándar
- `contenteditable` nativo del navegador

No requiere:

- jQuery
- frameworks
- dependencias externas
- compilación previa

---

# Características principales

Jocarsa Editor incluye:

- edición visual WYSIWYG
- sincronización automática con `textarea`
- integración directa en formularios HTML
- barra de herramientas visual
- encabezados y párrafos
- selección de familia tipográfica
- selección de tamaño de fuente
- color de texto
- color de resaltado
- negrita
- cursiva
- subrayado
- tachado
- listas ordenadas
- listas desordenadas
- citas
- líneas horizontales
- inserción de tablas
- alineación izquierda
- centrado
- alineación derecha
- justificado
- inserción de enlaces
- eliminación de enlaces
- limpieza de formato
- deshacer
- rehacer

---

# Demo pública

Existe una versión accesible públicamente mediante GitHub Pages:

https://jocarsa.github.io/jocarsa-editor/

Puede utilizarse libremente para pruebas y evaluación.

---

# Instalación

Clonar el repositorio:

```bash
git clone https://github.com/jocarsa/jocarsa-editor.git
````

Entrar en el directorio:

```bash
cd jocarsa-editor
```

---

# Uso básico

Incluir los archivos en el documento HTML:

```html
<link rel="stylesheet" href="jocarsa-editor.css">
<script src="jocarsa-editor.js"></script>
```

Crear un `textarea` con la clase correspondiente:

```html
<textarea class="jocarsa-editor" name="contenido"></textarea>
```

El editor se inicializa automáticamente al cargar la página.

---

# Ejemplo completo

```html
<!doctype html>
<html lang="es">
<head>
	<meta charset="utf-8">
	<title>Mi editor</title>
	<link rel="stylesheet" href="jocarsa-editor.css">
</head>
<body>

<form method="post">

	<textarea class="jocarsa-editor" name="contenido">
<h2>Hola mundo</h2>
<p>Este es un ejemplo.</p>
	</textarea>

	<input type="submit" value="Guardar">

</form>

<script src="jocarsa-editor.js"></script>

</body>
</html>
```

---

# Funcionamiento interno

El sistema:

1. detecta automáticamente todos los `textarea.jocarsa-editor`
2. oculta el `textarea` original
3. genera una interfaz visual editable
4. mantiene sincronizado el HTML interno con el `textarea`

De esta forma, al enviar el formulario:

```html
<form method="post">
```

el servidor recibe directamente el HTML generado.

---

# Personalización

Todo el aspecto visual puede modificarse desde:

```bash
jocarsa-editor.css
```

Se pueden personalizar fácilmente:

* colores
* bordes
* sombras
* tipografías
* tamaño de botones
* distribución de la barra

---

# Filosofía del proyecto

Jocarsa Editor nace con una idea clara:

**proporcionar una herramienta visual de edición HTML completamente comprensible, sin depender de soluciones externas opacas o pesadas.**

Esto permite:

* aprender cómo funciona un editor visual
* adaptarlo libremente
* mantener independencia tecnológica
* integrarlo en cualquier proyecto propio

---

# Casos de uso recomendados

Jocarsa Editor resulta especialmente útil en:

* gestores de contenidos propios
* software educativo
* CRM internos
* ERP ligeros
* paneles administrativos
* herramientas de documentación
* edición de correos HTML
* plataformas de formación

---

# Compatibilidad

Compatible con navegadores modernos:

* Chrome
* Edge
* Firefox
* Brave
* Opera

---

# Estado del proyecto

Proyecto funcional y utilizable.

Puede evolucionar incorporando en el futuro:

* inserción de imágenes
* vista HTML / código fuente
* exportación enriquecida
* limpieza avanzada de pegado
* tablas avanzadas
* componentes multimedia

---

# Licencia

Uso libre.

Puede utilizarse, modificarse y adaptarse libremente en proyectos propios.

---

# Autor

José Vicente Carratalá
[https://github.com/jocarsa](https://github.com/jocarsa)

---

# Enlace oficial

Repositorio:

[https://github.com/jocarsa/jocarsa-editor](https://github.com/jocarsa/jocarsa-editor)

Demo:

[https://jocarsa.github.io/jocarsa-editor/](https://jocarsa.github.io/jocarsa-editor/)

