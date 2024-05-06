# BaseDeDatos_Project-Flights-Intro
El proyecto consiste en realizar un análisis exhaustivo de los datos de alquiler de autos en aeropuertos con el objetivo de comprender mejor los patrones de comportamiento de los pasajeros y optimizar las estrategias de marketing y publicidad de una agencia de alquiler de autos.


# Modelo 1 - Recomendación de Publicidad para Agencia de Renta de Carros en Aeropuertos

## Duración de los vuelos:

Los meses con estancias más largas en los destinos implican un mayor número de días de alquiler de autos.

- ¿Cuál es el promedio de días de estancia de los pasajeros en los destinos a lo largo del año?
- ¿Cómo varía la duración de los alquileres de autos según el mes y el destino?

## Motivo del viaje:

Esta información nos ayuda a determinar qué tipo de carro ofrecer según el mes. Por ejemplo, un viaje familiar podría requerir un vehículo más grande, mientras que un viaje de negocios puede preferir un automóvil más elegante y compacto.

- ¿Cuáles son los principales motivos de viaje de los pasajeros en cada mes del año?
- ¿Qué tipo de vehículos son más demandados para viajes de negocios en comparación con los viajes de ocio?

## Destino del viaje:

Nos proporciona datos sobre el tipo de vehículo que debemos promocionar más en los distintos meses del año para los distintos destinos del mundo. Por ejemplo, en destinos de playa podríamos promocionar descapotables, mientras que en ciudades urbanas podríamos destacar los autos compactos.

- ¿Qué destinos son más populares en cada estación del año?
- ¿Cuál es la preferencia de vehículos en destinos urbanos frente a destinos rurales durante los meses de verano?

## Conexión del vuelo:

Esta información nos brinda datos para saber qué tipo de publicidad ofrecer. Según el tiempo promedio de espera, podemos determinar qué tan elaborada en tiempo debe ser la publicidad. Por ejemplo, en aeropuertos con largas esperas, la publicidad puede ser más detallada y persuasiva.

- ¿Cuál es el tiempo promedio de espera de los pasajeros en los aeropuertos durante diferentes meses del año?
- ¿Cómo varía la efectividad de la publicidad según el tiempo de espera en los aeropuertos?

## Tipo de boleto:

Esta información nos permite comprender qué tipo de lujo está buscando el usuario en los distintos destinos. Así, podemos ofrecer publicidad más personalizada para el tipo de usuario y destino. Por ejemplo, para viajes de primera clase podríamos promocionar autos de lujo, mientras que para vuelos económicos podríamos ofrecer opciones más accesibles.

- ¿Qué porcentaje de pasajeros viaja en primera clase en comparación con los que viajan en clase económica?
- ¿Cuál es la relación entre el tipo de boleto y la preferencia de vehículos de alquiler en distintos destinos?

## Tipo de equipaje:

Nos brinda datos sobre el tamaño del vehículo que debemos ofrecer, dependiendo de la cantidad de maletas que viajan y la cantidad de espacio que se necesita. Por ejemplo, para viajeros con mucho equipaje podríamos promocionar vehículos con mayor capacidad de carga.

- ¿Cuál es el tamaño de vehículo más solicitado por clientes que viajan con una gran cantidad de equipaje?
- ¿Cómo se puede adaptar la oferta de vehículos para satisfacer las necesidades de los clientes en función del tamaño de su equipaje?

## Entidades:

### Pasajero:
- Id_pasajero 
- Id_vuelo
- Id_renta_carro
- age
- gender

### Vuelo: 
- Id_vuelo
- Id_pasajero
- airline 
- from
- to
- day
- month
- year
- duration

### Alquiler de Auto:
- Id_renta_carro
- Id_pasajero 
- reason 
- stay
- connection 
- wait
- ticket
- checked_bags
- carry_on

## Recomendaciones:

### Para la empresa de alquiler de coches:

- **Optimización de la Publicidad Basada en el Tráfico de Vuelos:**
  - **Análisis de Datos:** Implementar un análisis de datos riguroso para determinar los meses de mayor actividad de vuelos por aeropuerto. Utilizar esta información para dirigir la publicidad hacia esos períodos de alta afluencia.
  - **Inversión Estratégica:** Asegurar que la inversión en publicidad se alinee con los picos de tráfico identificados, aumentando así la visibilidad de la marca en momentos clave.
- **Integración de Tecnologías de Predicción:**
  - **Modelos Predictivos:** Desarrollar modelos que utilicen datos históricos para prever la demanda futura de alquiler de coches. Esto permitirá a la empresa ajustar su oferta de servicios y disponibilidad de vehículos de acuerdo a las proyecciones de afluencia de viajeros.
- **Colaboraciones Estratégicas:**
  - **Asociaciones con Aerolíneas y Aeropuertos:** Establecer colaboraciones con aerolíneas y aeropuertos para ofrecer promociones o descuentos exclusivos a los viajeros que llegan. Esto podría incluir ofertas que se presenten durante las experiencias virtuales ofrecidas en los aeropuertos.
  - **Paquetes Conjuntos:** Desarrollar paquetes de servicios que incluyan alquiler de coche y experiencias virtuales como un producto combinado, incentivando así a los viajeros a planificar sus necesidades de transporte y entretenimiento de manera conjunta.

- **Marketing y Experiencias Personalizadas:**
  - **Promociones Personalizadas:** Utilizar la información obtenida de las actividades de vuelos y preferencias de los viajeros para crear ofertas personalizadas que se ajusten a las necesidades y planes de viaje de los clientes.
  - **Experiencia del Usuario Mejorada:** Ofrecer un proceso de reserva más fluido y opciones de personalización del alquiler (como la elección del modelo de coche, accesorios adicionales, etc.) para mejorar la experiencia del cliente.

- **Expansión de la Oferta de Servicios:**
  - **Puntos de Alquiler Flexibles:** Considerar la expansión de puntos de servicio dentro de los aeropuertos o en ubicaciones cercanas para facilitar el acceso y la comodidad de los usuarios.
  - **Servicios Adicionales:** Explorar la oferta de servicios adicionales como el alquiler de equipos especializados (sillas para niños, GPS, etc.) para atraer a un segmento más amplio de clientes.
