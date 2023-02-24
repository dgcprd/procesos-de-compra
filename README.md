![DGCP](https://www.dgcp.gob.do/wp-content/themes/dgcp/img/logo-dgcp-extendido.svg)

# Procesos de Compra #

_Muestra los detalles de los procesos de compra gestionados a través del Sistema Electrónico de Contrataciones Públicas (SECP) - Portal Transaccional_

Dentro de este repositorio podrán encontrar 2 archivos zip que corresponden a plugins para agregar los detalles de las compras hechas a través del portal transaccional.

### Configuración del plugin de Joomla ###

* Descargar el archivo ZIP ___mod_processes.zip___ que se encuentra en la carpeta ___joomla___
* En su administrador de Joomla dirigirse al apartado ___Instalar Extensiones___
![Instalar Extensiones](https://user-images.githubusercontent.com/126279066/221255019-bc4a3516-66dc-4c55-a697-7614e5056d9c.png)
* Una vez allí subira el ZIP descargado a travez de la opción __Subir e instala extensión de Joomla__
![Subir e instala extensión de Joomla](https://user-images.githubusercontent.com/126279066/221257075-e28f9a52-bb16-4386-9c0b-ca1f54496f99.png)
* Justo después el sistema le indicará si el proceso fue exitoso
![Éxito](https://user-images.githubusercontent.com/126279066/221256916-a7318977-c3a9-4769-ba63-6255d439aa07.png)
* Su siguiente paso es ir a la sección de Modulos
![Modulos](https://user-images.githubusercontent.com/126279066/221277380-bea1c62a-0a03-4a9a-9ff0-887934c88a90.png)
* Busque el llamado ___Procesos de Compra___
![busqueda](https://user-images.githubusercontent.com/126279066/221277626-ba31dbd5-27af-4102-8449-7cf22851d861.png)
* Al abrir la ___configuración____ para activarlo verá una pantalla similar a la siguiente:
![Configuración](https://user-images.githubusercontent.com/126279066/221278863-617f24b2-466d-4048-a8c2-ac29c58738fe.png)
  * Todos los campos tienen una descripción al hacer posicionar el mouse sobre estos
  ![Hover](https://user-images.githubusercontent.com/126279066/221279072-2f2d6405-97a2-4f07-9f8f-6b72e7b45b57.png)
  * Si no sabe cual es su código de unidad de compra o puede consultarlo en el enlace <a href="https://www.dgcp.gob.do/instituciones-implementadas/" target="_blank">https://www.dgcp.gob.do/instituciones-implementadas</a>.
  * Deberá editar las opciones deseadas, pero es fundamental que decida en que posición estará ubicado el mismo y cambia la visivilidad del mismo.
  ![Vista](https://user-images.githubusercontent.com/126279066/221279919-850859ec-75d3-4cfc-bcdd-727123dcc215.png)
  * Otro detalle significativo por configurar es los enlaces que podrán mostrar dicho modulo, puede elegir el de su elección o configurar para que aprezca en todas las páginas.
  * Precione el botón guardar para culminar la configuración.
  ![Menú](https://user-images.githubusercontent.com/126279066/221280327-43f961c8-9c86-4cf3-acfb-17e52cfcceb3.png)
* Finalizado el proceso anterior bastaría con ir a su artículo y colocar el siguiente fragmento de código en el mismo ___{loadmodule mod_processes}___
![Code](https://user-images.githubusercontent.com/126279066/221281273-914b988b-8c99-442f-a972-730c80589020.png)
* Justo al finalizar este proceso verá los procesos de compra publicados en su página.
![Listo](https://user-images.githubusercontent.com/126279066/221281943-20f13c79-30a4-4ff5-81dd-b365034dd264.png)


### Configuración del plugin de WordPress ###

* Descargar el archivo ZIP ___procesos-de-compras.zip___ que se encuentra en la carpeta ___wordpress___
* En su administrador de WordPress dirigirse al apartado ___Instalar Plugins___
![Plugins](https://user-images.githubusercontent.com/126279066/221282693-8d13af39-a73b-421b-804b-3686bbecd3b8.png)
* Una vez allí subira el ZIP descargado a travez de la opción __Subir Plugin__
![Subir e instalr plugin](https://user-images.githubusercontent.com/126279066/221283340-b08cf525-b5df-4d51-a5d0-8c466acda6f6.png)
* Justo después el sistema le indicará si el proceso fue exitoso
![Éxito](https://user-images.githubusercontent.com/126279066/221284203-0744e785-460c-40b8-a540-5b8ef18a08a6.png)
* Su siguiente paso es pulsar el botón ___Activar___ y le aparecerá en el menú administrativo la opción ___Configuración Procesos de Compra___
![Modulos](https://user-images.githubusercontent.com/126279066/221285212-3c474c80-6e94-44aa-9402-0dc5b9b7c129.png)
* Al abrir la opción aparecrá ___configuración____ y verá una pantalla similar a la siguiente:
  * Si no sabe cual es su código de unidad de compra o puede consultarlo en el enlace <a href="https://www.dgcp.gob.do/instituciones-implementadas/" target="_blank">https://www.dgcp.gob.do/instituciones-implementadas</a>.
  * Deberá editar las opciones deseadas.
  * Precione el botón ___Guardar Configuración__ para culminar la configuración.
  ![Guardado](https://user-images.githubusercontent.com/126279066/221285827-2584e8b6-4fb4-4d80-a769-3bdd4f8eb60d.png)
* Finalizado el proceso anterior bastaría con ir a su página y colocar el siguiente fragmento de código en el mismo ___[list_processes]___
![Code](https://user-images.githubusercontent.com/126279066/221286101-e0a94263-197c-4661-b2ff-e6e31cf8f19b.png)
* Justo al finalizar este proceso verá los procesos de compra publicados en su página.
![Listo](https://user-images.githubusercontent.com/126279066/221286208-b2449152-8d42-42c5-aedd-990354073e3c.png)

