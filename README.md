# AplicandoSASS-EstudioJuridico-Nardecchia
Entrega Aplicando SASS, volcando los conceptos vistos en la clase SASS I y su correspondiente repaso, en una landing page para estudio jurídico.

Se utilizó como base el proyecto presentado con anterioridad, conjuntamente con sus archivos, buscando cuidar funcionalidad y orden en forma conjunta con la aplicación 
del contenido de la Clase-13. 

Tomando la estructura HTML como guía, manteniendo el uso de bootstrap, se generó un archivo principal ("style.scss") para el uso de SASS. Conjuntamente, se creó la carpeta "base"
contenedora de archivos partial ("variables" y "listas"), los que fueron importados al archivo de SCSS principal, y cuya finalidad fue posibilitar la implementación de variables 
tales como colores de background y texto, sombreado, fuentes y bordes, buscando que ulteriormente repliquen en el CSS del sitio.

Por su parte, y para mantener un orden relativo en la aplicación del contenido de clase, se creó una carpeta contenedora denominada "components", que agrupaba un archivo partial 
por cada sección de la landing page, en las cuales se hizo uso de las variables mencionadas, transformaciones y estilado correspondiente a cada sección. Estas secciones también fueron importadas al archivo SCSS principal.

Por último, ante el obstáculo de carga que representa node_modules, se creó un archivo .gitignore para no sobrecargar el repositorio y generar errores.


