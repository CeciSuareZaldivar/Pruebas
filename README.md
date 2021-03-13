# 🏨  API Xacalli Posada

Creación de una API para el Hotel PetFriendly denominado [“Xacalli Posada”](https://www.facebook.com/XacalliEnTepoztlan), ubicado en Tepoztlán Morelos.

### 💡 Nota:

> Este proyecto se realizó cómo parte de la finalización del módulo de BackEnd de [Bedu](https://bedu.org/), el [equipo 1](#autores) creó la API implementando todo lo aprendido durante el módulo.


# 🚀 Requerimientos del proyecto

El hotel requiere agilizar su proceso de toma de decisiones dentro su área de ventas, necesita un espacio en el cual pueda visualizar y analizar los diferentes datos que sus huéspedes le proporcionan.

Algunos de los procesos son:
* **Seguimiento dentro del proceso de venta:** 
    * Asignar un vendedor
    * Verificar disponibiidad:
        * Determinadas fechas
        * Las diferentes habitaciones
        * Servicios
* **Obtener sólo determinados campos de sus huéspedes:**
    * Estadisticas
        * Nacionalidad (¿De dónde los visitan?)
        * No. noches que se hospedan
        * Valoración (Calificación que los húespedes le asignan a su estadía)
    * Remarketing:
        * El e-mail de los húespedes para enviar promociones

# 🎯 Objetivo

Agilizar los procesos dentro del área de ventas del hotel, mediante la estructuración y configuración de un CRM (Customer Relationship Management) personalizado.

La correcta implementación del proyecto por parte del hotel se traducirá cómo la optimización en la toma de decisiones dentro de su departamento de ventas; el CRM agilizará no sólo la visualización si no también la gestión de sus diferentes datos.

# 📖 Desarrollo del Proyecto

## 👱 Usuarios

#### Tipos de Usuarios 

Para el correcto funcionamiento de la API, únicamente se requieren 2 usuarios. Mismos que se detallan a continuación:

##### Cliente (Huésped)

Individuo que pide informes del hospedaje, deseando reservar una determinada fecha para hospedarse en el hotel.


Suele proporcionar los siguientes datos para preguntar sobre la disponibilidad :
* Nombre Completo
* Teléfono
* Fechas de la reservación:
    * Inicio
    * Fin
* No. de personas a hospedarse
* No. mascotas que viajan con ellos

###### Historias de usuario
Únicamente puede agregar sus datos para pedir informes de su reservación.

##### Vendedor
Responsable del seguimiento de renta de las cabañas.


Entre sus principales funciones destacan: 
* Brindar informes del hospedaje
* Verificar disponibilidad de las habitaciones.
* Darle seguimiento en general a todas las dudas del cliente/huésped con la finalidad de que
confirme su reservación.

###### Historias de usuario
Este usuario puede realizar las siguientes acciones:
* Agregar Clientes
* Modificar Clientes
* Eliminar Clientes
* Consultar atributos específicos de los Clientes

## 📝 Creación de la Base de Datos

### Entidades

* Empleado
* Cliente
* Habitación
* Opinión 
* Cliente_habitación
* Cliente_servicio

### Modelo ER
![modelo_er](./img/modelo_er.jpg)

### Modelo relacional
![modelo_relacional](./img/modelo_relacional.jpg)

# Implementacón del Proyecto
## Preparar entorno de desarrollo
Crear la siguiente estructura 

<a name="autores"></a>
# ✒️ Autores 

[![Ceci Suarez](./img/ceci_suarez.jpg)](https://github.com/CeciSuareZaldivar) [![Cristian Garcia](./img/cristian_garcia.jpg)](https://github.com/Adalk033)  
[![David Velazquez](./img/david_velazquez.jpg)](https://github.com/dvmoran1) [![Julian Hernandez](/img/julian_hernandez.jpg)](https://github.com/codeinit-code)


# 🎁  Agradecimiento Especial

Todos los integrantes del equipo 1, agradecemos infinitamente la oportunidad que nos brindaron **Santander** y **Bedu** de participar dentro del programa __“Becas Santander – BEDU: Disruptive Innovation: 3 caminos para impulsar tu carrera"__, en el Learning Path **Desarrollo Web**.

Somos muy afortunados de formar parte de este gran proyecto. 
Esperamos nos honren con la oportunidad de continuar retando nuestro potencial en la siguiente fase del programa.  
