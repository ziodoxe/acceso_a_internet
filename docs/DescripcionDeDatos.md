# Descripción del conjunto de datos:

------------

## Cantidad de Instancias:

El conjunto de datos se compone de 54178 filas, de las cuales se analizarán 1144 que corresponden a las ciudades de Rio Grande y Ushuaia, cada una de ellas representando una observación única que hace referencia a la encuesta realizada por el INDEC en el marco de la Encuesta Permanente de Hogares (EPH) a nivel nacional en el cuarto trimestre del año 2018.

## Diseño de registros de la base de personas

Tipo de campo: 
* N = Numérico
* C = Carácter

---------

- Campo: CODUSU
- Tipo (longitud): C(29)
- Descripción: Código   para   distinguir   viviendas,   permite  aparearlas  con  Hogares  y  Personas.  Además  permite  hacer  el  seguimiento  a  través  de  los  trimestres.

- Campo: NRO_HOGAR
- Tipo (longitud): N (1)
- Descripción: Código para distinguir hogares, permite aparearlos con Personas.
51 = Servicio doméstico en hogares 
71 = Pensionistas en hogares

- Campo: COMPONENTE
- Tipo (longitud): N (1)
- Descripción: Número de componente: n° de orden que se asigna a las personas que conforman cada hogar de la vivienda. Casos especiales: 
51 = Servicio doméstico en hogares 
71 = Pensionistas en hogares

- Campo: ANO4
- Tipo (longitud): N (4)
- Descripción: Año de relevamiento (4 dígitos).

- Campo: TRIMESTRE
- Tipo (longitud): N (1) 
- Descripción: Ventana de observación:
1  =  1°  trimestre 
2  =  2°  trimestre 
3  =  3°  trimestre 
4 =  4°   trimestre

- Campo: AGLOMERADO
- Tipo (longitud): N (1)
- Descripción: Código de aglomerado:
02 = Gran La Plata
03 = Bahía Blanca-Cerri
04 = Gran Rosario
05 = Gran Santa Fe
06 = Gran Paraná
07 = Posadas
08 = Gran Resistencia
09 = Comodoro Rivadavia-Rada Tilly
10 = Gran Mendoza
12 = Corrientes
13 = Gran Córdoba
14 = Concordia
15 = Formosa
17 = Neuquén-Plottier
18 = Santiago del Estero-La Banda
19 = Jujuy-Palpalá
20 = Río Gallegos
22 = Gran Catamarca
23 = Salta
25 = La Rioja
26 = San Luis-El Chorrillo
27 = Gran San Juan
29 = Gran Tucumán-Tafí Viejo 
30 = Santa Rosa-Toay
31 = Ushuaia-Río Grande
32 = Ciudad Autónoma de Buenos Aires
33 = Partidos del Gran Buenos Aires
34 = Mar del Plata-Batán
36 = Río Cuarto
38 = San Nicolás-Villa Constitución
91 = Rawson-Trelew

- Campo: POND_TIC
- Tipo (longitud): N (4)
- Descripción: Ponderación ajustada por no respuesta de TIC.

- Campo: IP_III_04
- Tipo (longitud): N (1)
- Descripción: En los últimos meses, ¿utilizó internet? 
1 = Sí 
2 = No 
9 = Ns/Nr

- Campo: IP_III_05
- Tipo (longitud): N (1)
- Descripción: En los últimos tres meses, excluyendo el uso de 
internet, ¿utilizó computadora? 
1 = Sí 
2 = No 
9 = Ns/Nr

- Campo: IP_III_06
- Tipo (longitud): N (1)
- Descripción: En los últimos tres meses, ¿utilizó un teléfono móvil (celular)? 
1 = Sí 
2 = No 
9 = Ns/Nr


## Diseño de registros de la base hogar

Tipo de campo: 
* N = Numérico
* C = Carácter

---------

- Campo: CODUSU
- Tipo (longitud): C(29)
- Descripción: Código   para   distinguir   viviendas,   permite  aparearlas  con  Hogares  y  Personas.  Además  permite  hacer  el  seguimiento  a  través  de  los  trimestres.

- Campo: NRO_HOGAR
- Tipo (longitud): N (1)
- Descripción: Código para distinguir hogares, permite aparearlos con Personas.
51 = Servicio doméstico en hogares 
71 = Pensionistas en hogares

- Campo: REALIZADA
- Tipo (longitud): N (1)
- Descripción: Entrevista realizada. Se refiere a la respuesta del hogar respecto al módulo.
1 = Sí
2 = No

- Campo: ANO4
- Tipo (longitud): N (4)
- Descripción: Año de relevamiento (4 dígitos).

- Campo: TRIMESTRE
- Tipo (longitud): N (1) 
- Descripción: Ventana de observación:
1  =  1°  trimestre 
2  =  2°  trimestre 
3  =  3°  trimestre 
4 =  4°   trimestre

- Campo: AGLOMERADO
- Tipo (longitud): N (1)
- Descripción: Código de aglomerado:
02 = Gran La Plata
03 = Bahía Blanca-Cerri
04 = Gran Rosario
05 = Gran Santa Fe
06 = Gran Paraná
07 = Posadas
08 = Gran Resistencia
09 = Comodoro Rivadavia-Rada Tilly
10 = Gran Mendoza
12 = Corrientes
13 = Gran Córdoba
14 = Concordia
15 = Formosa
17 = Neuquén-Plottier
18 = Santiago del Estero-La Banda
19 = Jujuy-Palpalá
20 = Río Gallegos
22 = Gran Catamarca
23 = Salta
25 = La Rioja
26 = San Luis-El Chorrillo
27 = Gran San Juan
29 = Gran Tucumán-Tafí Viejo 
30 = Santa Rosa-Toay
31 = Ushuaia-Río Grande
32 = Ciudad Autónoma de Buenos Aires
33 = Partidos del Gran Buenos Aires
34 = Mar del Plata-Batán
36 = Río Cuarto
38 = San Nicolás-Villa Constitución
91 = Rawson-Trelew

- Campo: POND_TIC
- Tipo (longitud): N (4)
- Descripción: Ponderación ajustada por no respuesta de TIC.

- Campo: IH_II_01
- Tipo (longitud): N (1)
- Descripción: En este hogar, ¿tienen computadora/s?
1 = Sí
2 = No
9 = Ns/Nr

- Campo: IH_II_02
- Tipo (longitud): N (1)
- Descripción: En este hogar, ¿disponen de acceso a internet?
1 = Sí
2 = No
9 = Ns/Nr


**Fuente de Datos:**
El dataset se obtuvo de la pagina [] https://sitioanterior.indec.gob.ar/bases-de-datos.asp