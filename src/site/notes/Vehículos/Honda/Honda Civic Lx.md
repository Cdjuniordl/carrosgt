---
{"dg-publish":true,"permalink":"/vehiculos/honda/honda-civic-lx/","tags":["gardenEntry"]}
---



## Datos del Vehículo 
### Foto:: 
![IMG_20230801_110146_407.jpg|250](/img/user/Adjuntos/IMG_20230801_110146_407.jpg)

### Marca:: Honda 
### Modelo:: Civic Lx
### Año:: 2007
#### Motor:: 1800
#### Serie Motor:: R18A1
#### Vin:: 2HGFG12607H548617
##### Placa:: 287FWB
##### Color:: Azul
---
## Falla reportada:
- El vehículo pierde potencia, cuando enciende la luz de check no acelera a más de 3mil RPM.

- Ya se le cambió grado de aceite de 20W50 a 10W30
- Se cambió la Válvula VTEC

---

## Diagnóstico:
### DTC::  P2647

[DTC Honda](http://aitus.golo365.com/Home/Report/reportDetail/diagnose_record_id/81b6b166ge8cOM5454OM2YnR2Y/report_type/D/l/es/timezone/-6)

Válvula VTEC atascada en abierto.
- Válvula VTEC reemplazada, es genérica.

- Falla presente en bajas temperaturas
- El vehículo presenta la falla únicamente al estar abajo de 85°C 
- Arriba de 85°C la falla no se presenta 

**Pruebas desde el escáner y mediciones con osciloscopio:**

##### Gráfica en Frío 
![U2023_7_26_8_45_16.jpg](/img/user/Adjuntos/U2023_7_26_8_45_16.jpg)

>[!info] Conexiones
>Canal1 (amarillo): Sensor de presión de aceite 
>Canal2 (azul): Señal activación de VTEC


>*Nota:* Sensor de presión mantiene señal de presión alta, mientras que la válvula VTEC está cerrada eléctricamente.
Posiblemente falla mecánica en válvula VTEC 

##### Gráfica en Caliente 
![U2023_7_29_4_10_41.jpg](/img/user/Adjuntos/U2023_7_29_4_10_41.jpg)

![U2023_8_2_0_53_45.jpg](/img/user/Adjuntos/U2023_8_2_0_53_45.jpg)

>[!info] Conexiones
>Canal1 (amarillo): Sensor de presión de aceite 
>Canal2 (azul): Señal activación de VTEC
>

>*Nota:* Presión de aceite cae al mismo tiempo que la válvula VTEC se cierra eléctricamente, indicando funcionamiento mecánico correcto de la VTEC.

---

## Reparación 
Cambio de cuerpo completo de válvula VTEC (sensor y válvula). Se reemplazo por una válvula original usada.

##### Válvula VTEC genérica 
![IMG_20230724_121718_325.jpg|300](/img/user/Adjuntos/IMG_20230724_121718_325.jpg)

>*Nota:* Se realizaron las mismas pruebas, sin arrojar fallas en cada una, tanto en frío como en caliente.

Vehículo entregado a prueba al cliente, sin reporte de fallas 

---



###### TAG:: #VTEC, #P2647 , #Honda , #Civic

