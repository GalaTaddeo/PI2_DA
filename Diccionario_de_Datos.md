# Diccionario de datos: 


>  ***Homicidios*** es un dataset que contiene datos relacionados con los siniestros viales de la Ciudad Autónoma de Buenos Aires. Contiene 2 hojas llamadas: **hechos** y **víctimas**.
 

* Las variables que contiene en **HECHOS** son:  

    * **ID**: Identificador unico del siniestro.
    * **N_VICTIMAS**: Cantidad de víctimas.
    * **FECHA**: Fecha en formato dd/mm/aaaa.
    * **AAAA**: Año.
    * **MM**: Mes.
    * **HORA**: Hora del siniestro.
    * **HH**: Franja horaria entera.
    * **LUGAR_DEL_HECHO**: Dirección del hecho.
    * **TIPO_DE_CALLE**: Tipo de arteria. En el caso de intersecciones a nivel se clasifica según la de mayor jerarquía:
        * **calle**: Arteria cuya calzada tiene un ancho comprendido entre cinco (5) y trece (13) metros. Inlcluye pasajes.
        * **avenida**:	Arteria cuya calzada tiene un ancho total de por lo menos trece (13) metros.
        * **autopista**: Vía multicarril con calzadas para ambas manos separadas físicamente, sin cruces a nivel, con accesos controlados y sin ingreso directo desde los predios frentistas lindantes. Incluye AU 25 de mayo, AU Perito Moreno, AU Dellepiane, Av Lugones, Av. Cantilo, AU Frondizi, AU Buenos Aires - La Plata en el tramo que circula dentro de la Ciudad de Buenos Aires y Paseo del Bajo. Incluye ingresos y egresos de las mismas y distribuidores.
        * **general paz**: Avenida General Paz, ambos sentidos. Incluye ingresos y egresos de las mismas, distribuidores y calle colectora.
    * **Calle**: Nombre de la arteria donde se produjo el hecho.
    * **Altura**: Altura de la arteria donde se produjo el hecho.
    * **Cruce**: Cruce en caso de que sea una encrucijada.
    * **Dirección Normalizada**: Direccion en formato normalizado USIG.
    * **COMUNA**: Comuna de la ciudad (1 a 15).
    * **XY (CABA)**: Geocodificación plana.
    * **pos x**: Longitud con separador punto. WGS84.
    * **pos y**: Latitud con separador punto. WGS84.
    * **PARTICIPANTES**: Conjunción de víctima y acusado:
        * **MULTIPLE**: Cuando participan más de un vehículo como contraparte de la víctima.
    * **VICTIMA**: Vehículo que ocupaba quien haya fallecido a se haya lastimado a raíz del hecho, o bien peatón/a. Clasificación agregada del tipo de vehículos:
        * **PEATON**: Víctima distinta de cualquier ocupante de un vehículo, ya sea un conductor/a o un pasajero/a. Se incluyen los ocupantes o personas que empujan o arrastran un coche de bebé o una silla de ruedas o cualquier otro vehículo sin motor de pequeñas dimensiones. Se incluyen también las personas que caminan empujando una bicicleta o un ciclomotor.
        * **MOTO**: Vehículo a motor no carrozado que incluye motocicleta, ciclomotor y cuatriciclo.
        * **AUTO**: Vehículo a motor destinado al transporte de personas, diferente de los motovehículos, y que tenga hasta nueve plazas (incluyendo al asiento del conductor) (Sedan, SUV, coupe, etc).
        * **CARGAS**: Vehículo a motor destiando al transporte de cargas, incluye camiones pesados (con o sin acoplado o semirremolque, etc., camión de recolección de residuos) y livianos (utilitarios, furgonetas, pick-ups, camioneta con caja de carga).
        * **BICICLETA**: Vehículo con al menos dos ruedas, que generalmente es accionado por el esfuerzo muscular de las personas que lo ocupan, en particular mediante pedales o manivelas. Incluye bicicletas de pedaleo asistido y/o con motor.
        * **PASAJEROS**: Personas lesionadas que se encuentran dentro, descendiendo o ascendiendo de las unidades de autotrasporte público de pasajeros/as y ómnibus de larga distancia.
        * **MOVIL**: Vehículos de emergencia: móviles policiales, ambulancias, autobombas.
        * **OTRO**: Otros vehiculos.
        * **SD**: Sin datos sobre el tipo de víctima.
    * **ACUSADO**: Vehículo que ocupaba quien resultó acusado/a del hecho, sin implicar culpabilidad legal:
        * **AUTO**: Vehículo a motor destinado al transporte de personas, diferente de los motovehículos, y que tenga hasta nueve plazas (incluyendo al asiento del conductor) (Sedan, SUV, coupe, etc).
        * **BICICLETA**: Vehículo con al menos dos ruedas, que generalmente es accionado por el esfuerzo muscular de las personas que lo ocupan, en particular mediante pedales o manivelas. Incluye bicicletas de pedaleo asistido y/o con motor.
        * **CARGAS**: Vehículo a motor destiando al transporte de cargas, incluye camiones pesados (con o sin acoplado o semirremolque, etc., camión de recolección de residuos) y livianos (utilitarios, furgonetas, pick-ups, camioneta con caja de carga).
        * **MOTO**: Vehículo a motor no carrozado que incluye motocicleta, ciclomotor y cuatriciclo.
        * **OBJETO FIJO**: Colisión contra objetos inmóviles fijados de manera permanente o semipermanente (columna, árbol, semáforo, etc.) o pérdidas de equilibrio de vehículos de dos ruedas que desencadenen la caída de sus ocupantes.
        * **PASAJEROS**: Personas lesionadas que se encuentran dentro, descendiendo o ascendiendo de las unidades de autotrasporte público de pasajeros/as y ómnibus de larga distancia.
        * **TREN**: Equipo móvil que se desplaza exclusivamente sobre rieles.
        * **OTRO**: Otros vehiculos.
        * **SD**: Sin datos sobre el vehículo participante.


* Las variables que contiene en **VICTIMAS** son: 

    * **ID_hecho**: Identificador unico del siniestro.
    * **FECHA**: Fecha en formato dd/mm/aaaa.
    * **AAAA**: Año.
    * **MM**: Mes.
    * **DD**: Día del mes.
    * **ROL**: Posición relativa al vehículo que presentaba la víctima en el momento del siniestro.
    * **VICTIMA**: Vehículo que ocupaba quien haya fallecido a se haya lastimado a raíz del hecho, o bien peatón/a. Clasificación agregada del tipo de vehículos:
        * **PEATON**: Víctima distinta de cualquier ocupante de un vehículo, ya sea un conductor/a o un pasajero/a. Se incluyen los ocupantes o personas que empujan o arrastran un coche de bebé o una silla de ruedas o cualquier otro vehículo sin motor de pequeñas dimensiones. Se incluyen también las personas que caminan empujando una bicicleta o un ciclomotor.
        * **MOTO**: Vehículo a motor no carrozado que incluye motocicleta, ciclomotor y cuatriciclo.
        * **AUTO**: Vehículo a motor destinado al transporte de personas, diferente de los motovehículos, y que tenga hasta nueve plazas (incluyendo al asiento del conductor) (Sedan, SUV, coupe, etc).
        * **CARGAS**: Vehículo a motor destiando al transporte de cargas, incluye camiones pesados (con o sin acoplado o semirremolque, etc., camión de recolección de residuos) y livianos (utilitarios, furgonetas, pick-ups, camioneta con caja de carga).
        * **BICICLETA**: Vehículo con al menos dos ruedas, que generalmente es accionado por el esfuerzo muscular de las personas que lo ocupan, en particular mediante pedales o manivelas. Incluye bicicletas de pedaleo asistido y/o con motor.
        * **PASAJEROS**: Personas lesionadas que se encuentran dentro, descendiendo o ascendiendo de las unidades de autotrasporte público de pasajeros/as y ómnibus de larga distancia.
        * **MOVIL**: Vehículos de emergencia: móviles policiales, ambulancias, autobombas.
        * **OTRO**: Otros vehiculos.
        * **SD**: Sin datos sobre el tipo de víctima.
    * **SEXO**: Sexo informado por fuente policial de la víctima.
    * **EDAD**: Edad de la víctima al momento del siniestro.
    * **FECHA_FALLECIMIENTO**: Fecha de fallecimiento de la víctima.