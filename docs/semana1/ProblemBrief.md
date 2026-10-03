# Problem Brief

## Decisión del problema

### Problema elegido

> El problema ganador en una frase, sin mencionar blockchain, y quién lo propuso.

Vasto número de bebidas alcohólicas contrabandeadas en el país. [Jhonathan Acevedo]

### Por qué elegimos este

> Qué inclinó al equipo por este problema frente a los demás, según los criterios de la Sesión 1.

Se realizo una investigacion y se ve un ejemplo en accion pero consideramos se puede mejorar su implementacion en el mercado.

### Propuestas descartadas

> Cada propuesta considerada, quién la propuso y el motivo del descarte.

Productos de calzado falsificados. Jhonathan Aceedo, no se profundizo en el metodo de implementacion. 

### Cómo tomamos la decisión

> Cómo llegó el equipo al acuerdo: votación, consenso tras debate u otro.

Debate, analisis y consenso entre todos los miembros del grupo.

---

## Problem Brief

### Encabezado

> Nombre del proyecto y una frase que describa el problema. Extensión: breve.

AvalCo, ¿Que tan seguro estoy de su procedencia?. 
A nivel nacional, de manera anual se llegan a incautar 100 mil bottellas de licor contrabandeadas o adulteradas.

### Equipo y roles

> Integrantes con su usuario de GitHub, rol asumido por cada persona, responsable de las entregas y canal de coordinación interna. Extensión: breve.

Jhonathan Acevedo (Katooa): Desarrollo, diseño y control de Apex. 
Al ser individual, simplemente se dedica las horas pertinentes en el tiempo libre para avanzar en el proyecto.

### Problema y evidencia

> Enunciado del problema en una frase, sin mencionar blockchain. Contexto, frecuencia y alcance. Evidencia mínima de que el problema existe: observación directa, experiencia propia, conversaciones o fuentes consultadas, con enlace o cita cuando aplique. Extensión: 150–300 palabras.

Vasto número de bebidas alcohólicas contrabandeadas en el país.

    Contexto: A nivel nacional, de manera anual se llegan a incautar 100 mil bottellas de licor contrabandeadas o adulteradas. 
    Link de referencia: "https://elpais.com/america-colombia/2024-12-09/colombia-se-incauta-de-100000-botellas-de-licor-al-ano.html"

    Frecuencia: Se estima que de cada 100 botellas, 24 se manejan en el mercado negro, fuera de la legalidad. 
    Link de referencia: "https://www.expreso.ec/actualidad/mundo/colombia-incauta-38-000-botellas-licor-contrabando-adulterado-165304.html"

    Alcance: Aunque afeca a todo el país, los departamentos con mayor afectasión por orden descendente son: Cundinamarca (Bogota D.C incluido), Antioquia, Valle del Cauca, Atlántico y Bolivar, esto debido a que son los departamentos con mayor consumo de licor. 
    Link de referencia: "https://www.pulzo.com/economia/estos-son-los-10-departamentos-mas-borrachos-de-colombia-PP51659"

Estudio: "https://repository.universidadean.edu.co/server/api/core/bitstreams/a7a4e755-e190-4744-b7e8-767ac1061f49/content"

### Usuario y actores

> Quién sufre el problema y qué necesita resolver. Cómo lo resuelve hoy y qué le cuesta en dinero, tiempo o esfuerzo. Demás actores que intervienen en el flujo, con el papel que cumple cada uno. Extensión: 150–300 palabras.

El problema tiene una ramificación de afectados los cuales incluye:
    -Estado: disminucion de las finanzas al no poder cobrar impuestos por las bebidas ilegales.
    -Sector Salud: los impuestos mencionados anteriormente no se pueden destinar a la salud como estipula la Constitucion colombiana.
    -Ciudadania: debido al licor adulterado, la salud de los ciudadanos se ve afectada tanto para estratos altos (aunque su afectacion mayormente seria economica) como bajos.
    -Sector Privado: perdidas millonarias por competencia desleal y daño a la reputación por el uso de estas marcas reconocidas como medio para vender las bebidas adulteradas.

En este caso, nos centramos en el sector privado y parte del estado (segun si la implementacion requiere o no aprovacion de por parte de la ley) ya que de ese modo podemos intervenir en toda la ramificacion por extensión.

Actualmente los entes que intervienen en este proceso son:
    -GOAT/GOA: encargados de la inspección de establecimientos, discotecas y eventos para decomizar la mercancia ilegal.
    -POLFA y Seccionales: encargados de las fronteras y puertos, asi como las redadas urbanas y controles viales.
    -DIAN: control el ingreso legal de licores extranjeros al país.
    -Fiscalía General de la Nación: desmantelan alambiques clandestinos e imputan los delitos de fraude aduanero.
    -Secretaría de Salud: controles para evitar intoxicaciones.
    -Sector Privado: encargadas de aplicar las medidas de mitigación y comercializar el producto.

Los métodos actuales para la lucha contra el contrabando son:
    -Tapas con válvulas de seguridad. Costo: ~$2000 COP por unidad.
    -Anillos de seguridad desprendibles. Costo: ~$2000 COP por unidad.
    -Vidrio contramarcado y pirograbado. Costo: centavos de pesos por unidad luego de la inversion inicial de la maquinaria.
    -Trazabilidad láser y códigos de lote. Costo: centavos de pesos por unidad luego de la inversion inicial de la maquinaria.
    -Puestos de control vial y planes de choque sectoral. Costo: minimo $800 MCOP anuales.
    -Código QR y SycTrace para cruce de datos en tiempo real. Costo: ~$250 COP promedio por unidad.

### Flujo actual de valor

> Recorrido paso a paso de cómo se mueve hoy el dinero, la información o el activo, desde el origen hasta el destino. Diagrama o secuencia numerada, con los intermediarios explícitos. Señalar si algún paso responde a una obligación normativa. Extensión: 150–300 palabras.

Paso 1: Origen (Producción Nacional o Importación)
    
    -El Activo: El licor sale de las fábricas nacionales (ej. destilerías departamentales) o llega a los puertos colombianos (si es importado).

    -La Información: Nace el historial digital del producto. El importador o productor registra el lote ante el INVIMA para la obtención del registro sanitario. Paralelamente, se ingresa la información de la mercancía en el sistema aduanero de la DIAN para emitir la Declaración de Importación.

    -El Dinero: El importador paga los aranceles correspondientes en los bancos autorizados por la DIAN para la nacionalización del producto.

Paso 2: El Eslabón de la Estampilla (Legalización Departamental)

    Las botellas se agrupan en bodegas autorizadas, donde operarios aplican físicamente la estampilla departamental en la tapa/cuello de cada envase. 

    Se utiliza la plataforma SYCTrace. Cada estampilla tiene un código de barras y un código QR único que vincula esa botella específica con datos exactos: marca, volumen, grado alcohólico y departamento asignado para su venta. Las Secretarías de Hacienda departamentales validan la asignación de ese cupo de estampillas. 

    El comercializador paga por adelantado el Impuesto al Consumo (ICO) y la tasa de la estampilla a la Unidad de Rentas del departamento respectivo. Sin este pago monetario, las estampillas no son liberadas.

Paso 3: Distribución Mayorista y Tránsito

    Camiones transportan las cajas de licor hacia los centros de distribución mayorista autorizados dentro de la región.

    Toda movilización entre departamentos requiere una Guía de Transporte o de Movilización electrónica generada en las plataformas fiscales. Si la policía vial detiene el camión, contrasta la información del sistema con el código QR de las cajas físicas.

    El distribuidor mayorista compra el inventario al productor/importador mediante transferencia bancaria y Facturación Electrónica (la cual desglosa de manera transparente el valor del producto, el IVA del 19% y el componente ad valorem del Impuesto al Consumo).

Paso 4: Venta Minorista (Establecimientos Comerciales)

    Las botellas llegan al destino comercial definitivo: bares, discotecas, supermercados o cigarrerías autorizadas.

    Los establecimientos registran el ingreso de la mercancía en sus inventarios. En esta etapa, los Grupos Operativos Anticontrabando (GOAT) pueden escanear de imprevisto las botellas en los anaqueles para auditar que el lote de información coincida en tiempo real con la base de datos de la Gobernación. 

    El minorista paga al distribuidor mayorista mediante crédito comercial o pasarelas de pago electrónico, soportado siempre por contabilidad legalizada.

Paso 5: El Destino Final (Consumidor)

    La botella es entregada en las manos del cliente. Tras el consumo, el establecimiento o el ciudadano destruye obligatoriamente la etiqueta y la tapa para evitar que la botella física regrese vacía al mercado ilegal. 

    El ciudadano digitaliza el código QR de la botella desde la app móvil de SYCTrace antes de consumirla. El sistema le devuelve una confirmación verde: "Producto Legal en este Departamento".

    El consumidor final paga en efectivo, tarjeta o billetera digital (como Nequi o Daviplata) el valor total reflejado en la factura comercial, cerrando el ciclo financiero de la cadena de valor legal.

### Fricciones identificadas

> Puntos concretos donde el flujo falla, se encarece o se demora. Cada fricción indica en qué paso ocurre, qué la causa y a quién afecta. Extensión: 150–300 palabras.

Escriban aquí su respuesta.

### Oportunidad e hipótesis

> Oportunidad priorizada entre las fricciones identificadas, con el motivo de la elección. Hipótesis inicial de por qué blockchain podría mejorar ese punto, expresada en términos de qué cambiaría para el usuario. Extensión: 150–300 palabras.

Escriban aquí su respuesta.

### Criterio de pertinencia

> Justificación de por qué el caso requiere un registro distribuido y no una base de datos tradicional o una integración entre sistemas existentes. Debe apoyarse en al menos uno de los criterios de la Sesión 1: varias partes que no confían entre sí necesitan compartir un mismo registro, el histórico no puede alterarse, o se elimina un intermediario que hoy concentra la confianza. Extensión: 150–300 palabras.

Escriban aquí su respuesta.

### Supuestos y riesgos

> Dos o tres supuestos que tendrían que ser ciertos para que la hipótesis funcione, y qué podría invalidarla. Extensión: 150–300 palabras.

Escriban aquí su respuesta.
