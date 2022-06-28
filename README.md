# Instrucciones convocatoria extraordinaria Periodismo de Datos

Hola

El martes 28 de junio de 09 a 12 AM en el aula 14.1.4 se realiza la convocatoria extraordinaria que se compone de una parte teórica y una práctica.

La parte teórica se compone de dos secciones.

- Una primera sección de preguntas y respuestas
- Una segunda sección con una pregunta de desarrollo
La parte práctica se compone de un ejercicio donde se combinan las cuatro prácticas que hemos realizado y el trabajo final. Por tanto, se abordará:

Un ejercicio práctico
Se explicará la metodología empleada.
El examen se realiza con el ordenador, se utilizará el Jupyter de UC3M y se publicará un proyecto en el repositorio de Github en PonteDatos.

Por tanto, se requiere:
- Ordenador portátil, como hemos ido utilizando durante el curso.
- Conexión a red WiFi de UC3M
- Un editor de Markdown, puede ser el propio de Jupyterhub.
- Acceso al Jupyterhub de UC3M (lo tienes si perteneces a esta clase, compruébalo a través de jupyterhub.uc3m.es/; si no lo tienes, coméntalo antes del examen.)
- Una cuenta en Github y estar en el grupo de clase
- Un programa cliente de git en los entornos Cygwin, WSL o Git Bash.
- Un repositorio en https://github.com/pontedatos/nombre-de-tu-cuenta-de-github. Si no eres todavía parte del equipo de "Ponte Datos" solicita serlo antes de empezar el examen o el día del examen antes de empezar.
- Una vez terminado el examen se sube a tu repositorio público y se crea una issue en el repositorio github.com/pontedatos/uc3m-periodismo-datos poniendo el enlace a la URL de tu repositorio; también se debe poner por aquí.

## Parte teórica
Tenéis que crear con nano un archivo denominado parte-teorica.md con dos secciones donde pongáis estas preguntas. Se ha de emplear sintaxis Markdown en todo el documento.

Este archivo lo utilizaréis luego en la parte práctica.


### P/R

1. ¿Qué fue determinante para el nacimiento del periodismo de datos moderno?
2. ¿Qué significa el funcionamiento "cliente-servidor"?
3. ¿Qué relación tiene el formato CSV con Excel?
4. ¿Qué tipos de formatos de datos hay? ¿Que similitudes y diferencias tienen?
5. ¿Qué tres tecnologías componen una página web?
6. Cuál es el primer comando que deberías usar en la terminal. Explica tu respuesta.
7. ¿Qué es una API. Pon algún ejemplo.
8. ¿Qué es Jupyter y para qué se utiliza? ¿Qué paradigma de programación desarrolla?
9. ¿Quién es Philip Meyer?
10. ¿Quién fue Florence Nightingale?

### Desarrolla

Cuando hablamos de periodismo o visualización de datos, ¿a qué datos nos referimos? Razona la respuesta.

## Parte práctica

1. Crea un repositorio en github.com/pontedatos con el nombre
compuesto por tu nombre de cuenta seguido de un guión medio corto seguido de la palabra extra. Es decir, si yo fuera quien lo creara la url del repositorio sería: https://github.com/pontedatos/flowsta-extra.
No añadas un README ni le pongas licencia, déjalo vacío.

2. Desde la terminal, crea un directorio con el mismo nombre que el repositorio y sigue las instrucciones de github para conectarlo.

3. Crea con nano un archivo README.md con las instrucciones de este examen en sintaxis Markdown.

4. Sube el README.md desde la terminal y comenta este cambio como "README del repositorio"

5. Copia el archivo "parte-teorica.md" al repositorio con el comando "cp" y comenta este cambio como "Añado la parte teórica"

6. Crea un cuaderno de Jupyter con el nombre "parte-practica.ipynb" desde donde te conectarás a la API covid19api.com. Tienes que practicar la programación literaria y explorar estos 3 países: España, Francia e Italia (aquí está la lista completa https://api.covid19api.com/countries). Para explorar en tiempo real sus datos y su histórico hay que conectarse a https://api.covid19api.com/country/PAIS/status/confirmed/live, donde PAIS es el nombre del país según la lista anterior. Analiza los datos de estos 3 países, plotéalo y crea una gráfica con los tres países. Guarda este archivo "parte-practica.ipynb" y también "parte-practica.md" en la carpeta del repositorio.

7. Edita README.md para enlazar los demás archivos del repositorio de forma relativa.

8. Configura el repositorio para que funcione "Pages". Compruébalo.

9. Pega tanto la URL del repositorio como la web en la issue y en esta tarea.
