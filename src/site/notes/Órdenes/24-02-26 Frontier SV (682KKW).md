---
{"dg-publish":true,"permalink":"/ordenes/24-02-26-frontier-sv-682-kkw/"}
---

<img src="https://lh3.googleusercontent.com/d/137fl3TIZ0-PU8b-Pt0bsjclwHub_u78G" width="150">

## Vehículo

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/vehiculos/nissan/frontier-682-kkw/#datos-del-vehiculo" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



## Datos del Vehículo 
### Foto:: 
<img src="https://lh3.googleusercontent.com/d/18t9KGsSyow-KNJV5kkOLTHYpW4Cfeb9U" Alt="Foto Vehiculo">

### Marca:: Nissan 
### Modelo:: Frontier SV 4x4
### Año:: 2014
#### Motor:: 4000
#### Serie Motor:: VQ40
#### Vin:: 1N6AD0EV3EN772111
##### Placa:: 682KKW
##### Color:: Gris Oscuro
---


</div></div>


## Recepción:
### Fecha:: 2024-02-26
#### Fotos de Recepción: 
<img src="https://lh3.googleusercontent.com/d/18udfD5URiF470KFtkqIltQ-2NZXVtnjh" width="250" Alt="Tablero">

###### Odómetro: 99 500Mi
###### Nivel de Gasolina: 1/4
###### Luces en tablero: Ninguna
###### Llaves o documentos: Llave y Contraseña primeras placas 

---

## Falla presentada:
- Códigos de falla de comunicación 


---

## Diagnóstico:
### DTC:: U1000

- <a href="https://usait.x431.com/Home/Report/reportDetail/diagnose_record_id/92f8735fgeKw8c8cDhAETdLrDh/report_type/D/l/es/timezone/-6"><button class="btn success">CÓDIGOS</button></a>
- Pérdida de comunicación con ECM y otro módulos 
- Solo se puede acceder a la ECM a través de *K-Line*

- Se procede a diagnosticar la **Red CAN**

#### Teoría de diagnóstico de la Red CAN
El sistema de red CAN funciona a través de 2 señales: *CAN-H* y *CAN-L* las cuales se encargan de hacer la comunicación entre los distintos módulos interconectados en el vehículo.

Existen varios factores a tener en cuenta:

1. Se debe identificar en el diagrama las posiciones de conexión de la red CAN para poder realizar las diferentes pruebas 
>[!info]- Conector DLC
> 
><img src="https://lh3.googleusercontent.com/d/1B9r39IanOPbLXT2NPnLvtrcJdnrT4cUA" width="240">
2. Resistencia interna de los módulos de conexión: Aproximadamente **60$\ohm$** con todos los módulos conectados y en buen estado.
>[!info]- Resistencia de Red CAN
>
><img src="https://lh3.googleusercontent.com/d/1B9eLo7jdkJ9V7kn8nP6v7ICy8UcuWNRP" width="230" >
3. Diagnosticar la gráfica de la señal de comunicación CAN utilizando el Osciloscopio, la cual debería verse de manera similar 
>[!info]- Gráfica de Red CAN
>
><img src="https://lh3.googleusercontent.com/d/1BAbCc3-xgLzsC2PFZF2lnGwh32nhAkdu" width="240">
>
><img src="https://lh3.googleusercontent.com/d/1BAdn6jeUUFUgwWRBZVMWc-VqIjKJKGSp" width="240">

#### Datos Obtenidos del Vehículo
##### Resistencia de Red CAN
<img src="https://lh3.googleusercontent.com/d/1BC2aY0RmGxjhBw5btgj2PzkG1KIzRemx" width="275">

##### Voltajes de línea CAN-H y CAN-L respectivamente 
<img src="https://lh3.googleusercontent.com/d/1BG2IVVmHFL5M2rRMM245vgWolam_mw7X" width="275">
<img src="https://lh3.googleusercontent.com/d/1BIS-m_kAXRoNrYWZo9fij-r0pD13ksak" width="275">

Segun los valores obtenidos notamos que aunque la resistencia se encuentra dentro de regla, los valores de voltaje están fuera del rango permitido, indicando un mal funcionamiento de la Red CAN

##### Gráfica de la Red CAN
<img src="https://lh3.googleusercontent.com/d/1BmWjMKPzcrdBdovnACjdEZaEhqYTrmyw" width="300">

<img src="https://lh3.googleusercontent.com/d/1BrUkBVj7smSfPcdig4Nnvp2bjNRBGKNG" width="300">

---
## Reparación:
- Aunque se encontraron valores fuera del rango en las señales de comunicación CAN, no se presentaron fallas en los módulos y tampoco se pudo volver a reproducir el código en ninguno de los módulos 
- Se realizó una prueba de manejo para comprobar el funcionamiento del vehículo 
- **Reporte de códigos después de la prueba** 

<iframe src="https://www.slideshare.net/slideshow/embed_code/key/jbrdRiimGTI7UO?hostedIn=slideshare&page=upload" width="320" height="400" frameborder="0" marginwidth="0" marginheight="0" scrolling="no"></iframe>

---

## Presupuesto:

<img src="https://lh3.googleusercontent.com/d/" Alt="Presupuesto">

---

###### TAG:: #Nissan , #Frontier 

---

## Estado

### Entrega:: 2024-03-06


