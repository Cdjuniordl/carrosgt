---
{"dg-publish":true,"permalink":"/vehiculos/honda/honda-civic-lx/"}
---



## Datos del Vehículo 
### Foto::
![](https://file.notion.so/f/s/188b5188-1a66-4356-8ff4-bfd8c46f7a2e/IMG_20230801_110146_407.jpg?id=df5e60d8-a79f-4814-935a-43f6b84432d9&table=block&spaceId=9f7b4746-1e57-4953-8d67-5e2115795754&expirationTimestamp=1691733600000&signature=OxyaoBxjPxRWcGdJ93tFA7TNfk3JHk2HiG72g0QTk4E&downloadName=IMG_20230801_110146_407.jpg)

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
![](https://file.notion.so/f/s/2c439092-b21a-4ab1-899b-18558d7cd406/U2023_7_26_8_45_16.jpg?id=c49280a9-e09d-4b94-81fa-b4d1739dbee6&table=block&spaceId=9f7b4746-1e57-4953-8d67-5e2115795754&expirationTimestamp=1691733600000&signature=INyRbwpechrySYkr9HkVeBiGvEcBq14tiu5Y7PQWssU&downloadName=U2023_7_26_8_45_16.jpg)


>[!info] Conexiones
>**Canal1** (amarillo): Sensor de presión de aceite 
>**Canal2** (azul): Señal activación de VTEC


>*Nota:* Sensor de presión mantiene señal de presión alta, mientras que la válvula VTEC está cerrada eléctricamente.
Posiblemente falla mecánica en válvula VTEC 

##### Gráfica en Caliente 
![](https://file.notion.so/f/s/08797cfc-6218-44be-b322-2738338f0004/U2023_7_29_4_10_41.jpg?id=889a97e5-beec-4d9c-8740-c35048dee496&table=block&spaceId=9f7b4746-1e57-4953-8d67-5e2115795754&expirationTimestamp=1691733600000&signature=qliuCzFxbBLQFC0bkjfnTgJyOYlWzREmslM5bZGFt8A&downloadName=U2023_7_29_4_10_41.jpg)


![](https://file.notion.so/f/s/991e3a8a-9bba-4b60-a2bb-d2e5fa8d22b9/U2023_8_2_0_53_45.jpg?id=e00966dd-6b26-409a-8cad-c111209328c2&table=block&spaceId=9f7b4746-1e57-4953-8d67-5e2115795754&expirationTimestamp=1691733600000&signature=0A3zvha-4LPiiDLeI5N2wN4h4JZEc0V60JlmXRzsN-4&downloadName=U2023_8_2_0_53_45.jpg)


>[!info] Conexiones
>**Canal1** (amarillo): Sensor de presión de aceite 
>**Canal2** (azul): Señal activación de VTEC
>

>*Nota:* Presión de aceite cae al mismo tiempo que la válvula VTEC se cierra eléctricamente, indicando funcionamiento mecánico correcto de la VTEC.

---

## Reparación 
Cambio de cuerpo completo de válvula VTEC (sensor y válvula). Se reemplazo por una válvula original usada.

##### Válvula VTEC genérica 
![](https://file.notion.so/f/s/31698545-5407-40be-a987-a793e10ab9ff/IMG_20230724_121718_325.jpg?id=c56defc5-89a9-4e62-b7c8-ffb28b4deafa&table=block&spaceId=9f7b4746-1e57-4953-8d67-5e2115795754&expirationTimestamp=1691733600000&signature=MPgNe59dQOWgUVd_gHo4lLZOIAz_tgN6TKg7yXPBQjk&downloadName=IMG_20230724_121718_325.jpg)


>*Nota:* Se realizaron las mismas pruebas, sin arrojar fallas en cada una, tanto en frío como en caliente.

Vehículo entregado a prueba al cliente, sin reporte de fallas 

---



###### TAG:: #VTEC, #P2647 , #Honda , #Civic

