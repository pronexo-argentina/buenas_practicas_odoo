Buenas Prácticas para el Desarrollo de odoo:

1- Se crea el ambiente de producción y ambiente testing.

2- Nada se prueba en el ambiente de producción solo se instalan módulos y se cargan maestros.

3- Se hace un respaldo cada 24h de producción.

4- Todas las pruebas de módulos se hacen en ambiente testing. Si funciona bien actualizamos Produccion.

5- No se desarrolla ni en testing ni en Producción sino local.

6- Las pruebas que el un módulo funciona no se hacen local sino testing y luego se pasa a producción.

7- Todos los días es necesario revisar los ciclos de venta/compra para ver que ningun cambio que se agrego afecte a Odoo.

9- Al terminar todos los dias hacer push e informar en el grupo los avances del proyecto.
