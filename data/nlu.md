## intent:saludo
- hola
- Muy buenas
- Epaa
- Hola!
- cómo estas?
- hola qué tal
- hola cómo estás?
- Aupa
- Aupi
- holi
- ey
- heey
- ola
- hola qué tal!
- Holaaaaaa
- Buenas
- Buenos días
- Buenas tardes
- Buenos diasss
- hola holaaa
- que hay?
- ¿Cómo va?
- Saludos
- buenos días
- hello!!!!!!!!!!!!!!!!!!!!!!!!!!!!
- Buenos dias

## intent:costo_promedio_falla
- el promedio de costo de fallas para la [HK-2029](matricula)
- el promedio de costo de fallas para la [HK-2029](matricula) entre [2016-12-13](fecha) y [2017-11-13](fecha)
- El costo promedio de la falla para [HK-2029](matricula)
- El costo promedio de fallas para [HK-2029](matricula)
- El costo promedio para [HK-4025](matricula)
- El costo promedio de fallas para [HK-4021](matricula)
- El costo promedio de fallas para [HK-2041](matricula)
- El costo promedio de fallas para [HK-2097](matricula)
- /costopromediofallas
- [HK-2029](matricula)

## intent:weather
- quiero clasificar un reporte
- clasificación de un sistema
- clasificar un reporte
- clasificación de falla
- clasificar reporte
- deseo clasificar una falla
- deseo clasificar un reporte
- clasificar
- clasificar una falla
- quiero clasificar un sistema
- clasificar falla
- quiero clasificar una falla
- /clasificar

## intent:city
- 06.01.2010 13:20:21 T. Ruiz Florez (FREDRUIF) Tel. 4255050 262\n[AIRE ACONDICIONADO NO SALE SUFICIENTE AIRE](descripcionReporte)

## synonym:descripcion
- descripción

## synonym:unidad
- unidades

## regex: fecha
- [0-9]{4}-[0-9]{2}-[0-9]{2}

## regex: matricula
- [a-zA-Z]{2}-[0-9]{4}

## regex:marcaTiempo
- [0-9]{2}.[0-9]{2}.[0-9]{4}[a-zA-Z]
