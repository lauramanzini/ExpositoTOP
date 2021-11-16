# Práctica 3 - Herramientas de calidad del software
Laura Manzini - *alu0101531700@ull.edu.es*

## ExpositoTOP
En esta práctica se utiliza el IDE IntelliJ para aprir el proyecto ExpositoTOP y crear un proyecto **Maven** para su análisis y control de calidad. Instalando una variedad de plugins por Maven se puede hacer un análisis más detallado del proyecto. Se comprobó la correcta funcionalidad de los plugins de Maven a través de la linea de comando utilizando las funcionalidades de Maven (site, compile ...)

A través de la herramienta **SonarQube** se hace también un control de calidad del proyecto escaneando el código y buscando problemas y fallos. Se encontró un problema muy impactante de seguridad que se solucionó sostituyendo la clase de java *Random* con la clase java *SecureRandom*.

Al final se generó la documentación del proyecto a través de la herramienta **Doxygen**. En la carpeta *Doxygen-documentation* encontramos las documentación producida por la herramienta, en particular hay dos carpetas que son:

* La carpeta *latex* contiene la documentación latex producida. Fue producido también un documento pdf llamado **_refman.pdf_** que contiene todas las informaciones sobre el proyecto.

* La carpeta *html* contiene las paginas web con todas las informaciones (clases, paquetes, ficheros ...) que constituyen el proyecto analizado. El fichero **_index_** nos lleva a la pagína web donde encotramos un resumen de la configuración de todo el proyecto.
