# sistema-venta-boletos

## Descripción

Este proyecto consiste en el diseño de un sistema de venta de boletos en línea para conciertos. 
El sistema permite a los usuarios buscar conciertos, seleccionar asientos disponibles, 
comprar boletos y recibir confirmaciones de compra.

---

### Relaciones entre las clases

## Usuario – Compra

La clase **Usuario** tiene relación con la clase **Compra**, porque un usuario puede realizar una o varias compras dentro del sistema.

Cada vez que un usuario adquiere boletos para un concierto, el sistema registra esa acción como una compra.


## Compra – Boleto

La clase **Compra** tiene relación con la clase **Boleto**, porque una compra contiene los boletos que el usuario adquiere.

Cuando un usuario realiza una compra, puede adquirir uno o varios boletos para un concierto.


## Boleto – Asiento

La clase **Boleto** tiene relación con la clase **Asiento**, porque cada boleto corresponde a un asiento específico dentro del lugar donde se realiza el concierto.

Esto permite controlar qué asientos están disponibles y cuáles ya fueron vendidos.


## Boleto – Concierto

La clase **Boleto** tiene relación con la clase **Concierto**, porque cada boleto permite el acceso a un concierto específico.

Cuando el usuario compra un boleto, este queda vinculado al concierto correspondiente.


## Concierto – Lugar

La clase **Concierto** tiene relación con la clase **Lugar**, porque cada concierto se realiza en un lugar determinado.

El lugar define características como su nombre, dirección y capacidad de personas.


## Concierto – Artista

La clase **Concierto** tiene relación con la clase **Artista**, porque los conciertos cuentan con uno o varios artistas que se presentan en el evento.

Además, un artista puede participar en diferentes conciertos.


## Lugar – Asiento

La clase **Lugar** tiene relación con la clase **Asiento**, porque los lugares donde se realizan los conciertos contienen los asientos disponibles para el público.

Estos asientos permiten organizar la distribución de los espectadores dentro del lugar.

#  Autor

David Hernandez Leyton
