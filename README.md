# sistema-venta-boletos

## Descripción

Este proyecto consiste en el diseño de un sistema de venta de boletos en línea para conciertos. 
El sistema permite a los usuarios buscar conciertos, seleccionar asientos disponibles, 
comprar boletos y recibir confirmaciones de compra.

---

##  Objetivos del Sistema

- Permitir la búsqueda de conciertos por nombre, fecha o artista.
- Mostrar disponibilidad de asientos.
- Permitir la compra de boletos.
- Generar confirmación de compra.

---

##  Modelo UML

El sistema está compuesto por las siguientes clases:

- Usuario
- Compra
- Boleto
- Asiento
- Concierto
- Lugar
- Artista

### Relaciones principales

- Un Usuario puede realizar múltiples Compras.
- Una Compra contiene uno o varios Boletos.
- Cada Boleto está asociado a un Asiento y un Concierto.
- Un Concierto se realiza en un Lugar.
- Un Concierto puede tener múltiples Artistas.
- Un Lugar contiene múltiples Asientos.

---

##  Diagrama de Clases

(Insertar aquí la imagen del diagrama UML)

---

##  Funcionalidades Principales

### Usuario
- buscarConcierto()
- comprarBoletos()

### Compra
- agregarBoleto()
- confirmarCompra()

### Boleto
- marcarVendido()

---

##  Tecnologías Utilizadas

- Modelado UML en StarUML
- GitHub para documentación

---

##  Autor

David Hernandez Leyton
