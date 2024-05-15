# BasesDeDatosPesca
Proyecto en el cual limpiamos un set de datos de la CONAPESCA de los años 2020,2021 y 2022. Para con ello normalizarlo hasta cuarta forma normal y poder extraer información de la pesca mexicana.

Pasos para replicar
1) Bajar los archivos de csv que estan en el archivo.rar y descomprimirlo, pues corregimos unas corrupciones de datos previo a meterlo a SQL y limpiarlo.
2) Crear una base de datos en SQL shell
3) Conectarla a tu IDE de postgres
4) Crear la tabla que aparece al inicio del codigo y importar los datos internamente de los csv
5) Correr la limpieza
6) Correr la parte de normalización que creara un schema nuevo y tablas, las cuales llenara de datos con los datos raw de la pesca.
7) Proceder a hacer las ventanas y querys bajo el nuevo schema de análisis de datos
8) Hacer las funciones de ventana para entrenamiento de modelos.

Los csv originales se encuentran en:
Producción Pesquera - datos.gob.mx/busca. (n.a.). Gob.mx. Recuperado mayo 15, 2024, de https://datos.gob.mx/busca/dataset/produccion-pesquera

Igualmente se incluyó el excel con algunas de las graficas de la sección análisis de datos del reporte escrito.
