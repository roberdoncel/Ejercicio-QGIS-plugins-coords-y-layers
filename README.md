# Ejercicio-QGIS-plugins-coords-y-layers
Ejercicio para practicar la creación de plugins en QGIS. Toma unas coordenadas, las transforma si es necesario, pide información adicional a servicio OSM y añade esto a una capa vectorial

Pequeño bug a mi parecer... Crea una nueva capa vectorial por cada nuevo elemento. Este código se rige de acuerdo a la resolución del ejercicio original, pero creo que debería comprobar si ya existe la capa.
