---
title: "¿Qué es la transmisión UDP?"
description: "El protocolo User Datagram Protocol (UDP) está basado en el intercambio de datagramas. Permite el envío de datagramas a través de la red sin que se haya establecido previamente una conexión, ya que el propio datagrama incorpora suficiente información de direccionamiento en su cabecera..."
pubDate: "Sep 12 2022"
heroImage: "/network.webp"
---

El protocolo User Datagram Protocol (UDP) está basado en el intercambio de datagramas. Permite el envío de datagramas a través de la red sin que se haya establecido previamente una conexión, ya que el propio datagrama incorpora suficiente información de direccionamiento en su cabecera. Tampoco tiene confirmación ni control de flujo, por lo que los paquetes pueden adelantarse unos a otros; y tampoco se sabe si ha llegado correctamente, ya que no hay confirmación de entrega o recepción.

El protocolo UTP proporciona un nivel de transporte fiable y está orientado a conexión. En cambio, el protocolo UDP, proporciona un nivel de transporte no fiable y se utiliza por ejemplo cuando se necesita transmitir voz o vídeo y resulta más importante transmitir con velocidad que garantizar el hecho de que lleguen absolutamente todos los bytes.

Las características principales de este protocolo son:

Trabaja sin conexión, es decir que no emplea ninguna sincronización entre el origen y el destino.
Trabaja con paquetes o datagramas enteros, no con bytes individuales como TCP. Una aplicación que emplea el protocolo UDP intercambia información en forma de bloques de bytes, de forma que por cada bloque de bytes enviado de la capa de aplicación a la capa de transporte, se envía un paquete UDP.
No es fiable. No emplea control del flujo ni ordena los paquetes.
Su gran ventaja es que provoca poca carga adicional en la red ya que es sencillo y emplea cabeceras muy simples.