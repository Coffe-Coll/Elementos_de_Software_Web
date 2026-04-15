1- Consulte y explique que significa a nivel de uso del internet: 
a. Servidor DNS 
b. IP 
c. Protocolo 
d. Nombre de dominio 
e. Directorio y nombre de archivo

R/: a. Servidor DNS:
Cuando escribes una URL en el navegador (por ejemplo, index.html no, sino una web real), el DNS traduce ese nombre a una IP.

En VS Code no lo ves directamente, pero pasa cuando pruebas tu página en internet.

b. IP:
Es la dirección del servidor donde está tu web.

Si usas algo como Live Server, tu página corre en algo como:

http://127.0.0.1:5500
Ese número es una IP local.

c. Protocolo:

Es lo que ves al inicio de la URL:

 http://
 https://

Indica cómo se comunican el navegador y el servidor.

d. Nombre de dominio:

Es el nombre de una web real (como google.com).
En VS Code tú trabajas localmente, pero cuando publicas tu web, usas un dominio.

e. Directorio y nombre de archivo:

Esto sí lo ves directamente en VS Code:
Ejemplo de carpetas:

/proyecto
   /imagenes
      foto.jpg
   index.html

Ruta: /imagenes/foto.jpg

2- Mencionamos dos roles importantes en el desarrollo de un producto web, pero hay otros roles involucrados, consulte y defina qué hace cada uno de los siguientes roles:
a. Diseñador UI/UX 
b. Cloud Manager / Ingeniero de infraestructura en la nube 
c. Administrador de base de datos 
d. Project Manager / Director del Proyecto

R/: a. Diseñador UI/UX:
Trabaja mucho con HTML y CSS en VS Code para que la web se vea bien y sea fácil de usar.

b. Cloud Manager:
No trabaja tanto en VS Code, pero se encarga de subir tu proyecto a internet (hosting, servidores).

c. Administrador de base de datos:
Puede usar VS Code para manejar archivos o conectar bases de datos (ej: MySQL).

d. Project Manager:
No programa directamente, pero usa herramientas para organizar el trabajo del equipo.

3- ¿Qué significa que un lenguaje sea turing completo?

R/: Un lenguaje como JavaScript (que sí usas en VS Code) puede hacer:

cálculos
decisiones (if)
ciclos (for, while)

Por eso es completo. Puedes crear programas complejos.

4- ¿Por qué CSS y HTML no son lenguajes de programación?

R/: Cuando escribes:

<h1>Hola</h1>

HTML solo estructura.

Y:

h1 {
  color: red;
}

CSS solo da estilo.

No puedes hacer cosas como:

decisiones (if)
ciclos (for)

Por eso no son lenguajes de programación.

5- Defina con sus palabras qué es una etiqueta en HTML. responde estas preguntas.

R/: En VS Code escribes etiquetas así:

<p>Este es un párrafo</p>

<p> = abre
</p> = cierra
lo de adentro = contenido

Sirven para construir toda la página.