# PR-Eclipse-02-EjemploLibreria

1. ¿Qué pasaría si exporto el proyecto a un .zip y se lo paso a un amigo o me lo llevo al ordenador de casa? ¿Funcionaría? Razona la respuesta.

Sí funcionaría, ya que el archivo JAR se encuentra dentro del proyecto.

2. ¿Qué pasaría si eliminas el archivo .jar de la carpeta lib? (puedes moverla a otro directorio para probarlo) ¿Qué ha pasado y por qué?

Ya no funciona, ya que no se puede hacer referencia a dicho archivo.

3. Y si agrego la librería con Add External JARs.... ¿Observas alguna diferencia en la configuración del Build Path? ¿Crees que si lo exporto a .zip y se lo paso a un compañero le funcionaría?

Se añade una ruta absoluta, que a nosotros nos funcionaría, pero si lo pasamos no funcionaría, ya que el archivo no se encuentra con el proyecto.

4. ¿Por qué no es recomendable usar Add External JARs… en proyectos que vas a compartir?

Ya que el otro usuario tendría que añadir todas las librerias que se estén utilizando.
