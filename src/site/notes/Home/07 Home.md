---
{"dg-publish":true,"permalink":"/home/07-home/"}
---



## Órdenes


<!DOCTYPE html>
<table width="340"style="text-align: center;">
  <tr  style= "background-color: #202020;">
    <td><a href="04 Clientes.md" class="internal-link"><img src="https://lh3.googleusercontent.com/d/1754ysjU9Eq7gj82N06631Cv9KiCTI6WZ" width="90" ></td>
    
    <td><a href="03 Todos.md" class="internal-link"><img src="https://lh3.googleusercontent.com/d/175HsVY2yY8Zz48zkZ6Hsyykw2cnVbptc" width="90"></td>
    
  </tr>
  <tr  style= "background-color: #202020;">
      <td style="vertical-align: middle; font-size: 16px;" ><a href="04 Clientes" class="internal-link"><center><strong>Clientes</strong></center></td>
    <td style="vertical-align: middle; font-size: 16px;" ><a href="03 Todos" class="internal-link"><center><strong>Vehículos</strong></center></td>
      </td>
    </tr>
</table>
<table width="340" style="text-align: center;">
  <tr  style= "background-color: #202020;">
    <td><a href="06 Órdenes en Proceso.md" class="internal-link"><img src="https://images.freeimages.com/fic/images/icons/50/buuf/128/a_icon_on_da_mic_for_showcasin_my_verbul_skiolls.png?" width="90"></td>
    
	<td><a href="05 Órdenes Completadas.md" class="internal-link"><img src="https://images.freeimages.com/fic/images/icons/50/buuf/128/at_pam_s_house_there_was_money_missing.png?"  width="90"></td>
  </tr>
  <tr  style= "background-color: #202020;">
      <td style="vertical-align: middle; font-size: 16px;" ><a href="06 Órdenes en Proceso" class="internal-link"><center><strong>Órdenes en Proceso</strong></center></td>
      <td style="vertical-align: middle; font-size: 16px;" ><a href="05 Órdenes Completadas" class="internal-link"><center><strong>Órdenes Completadas</strong></center>
    </tr>
  </table>


## Nuevos Datos

```button
name Nuevo Cliente
type note(Nombre) template
action tpl.Cliente
color green
```{ #button-aiqw}




```button
name Nuevo Vehículo
type note(Marca) template
action tpl.Datos
color purple
```{ #button-myet}


```button
name NUEVA ORDEN
type command
action Notas diarias: Abrir la nota de hoy
color yellow
```{ #button-p9k2}


## Pendientes

```button
name RECORDATORIOS
type link
action obsidian://open?vault=Carros%20Gt&file=Home%2F01%20Recordatorios
color red
```{ #button-fygj}


```button
name COBROS Y PAGOS
type link
action obsidian://open?vault=Carros%20Gt&file=Presupuestos%2FCOBROS%20Y%20PAGOS
color purple
```{ #button-fygj}


