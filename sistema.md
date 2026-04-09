# Sistema de Monitoreo de Temperatura para Invernadero

## Descripción General

Sistema interactivo que monitorea la temperatura y humedad dentro de un invernadero.
Activa ventiladores o calefactores automáticamente según las condiciones detectadas,
manteniendo el ambiente óptimo para el cultivo.

## Usuario Objetivo

Agricultores o técnicos agropecuarios que gestionan invernaderos de pequeña
y mediana escala, sin necesidad de conocimientos avanzados en electrónica.

## Entradas

|Sensor / Entrada|Tipo de señal|Descripción|
|-|-|-|
|Sensor de temperatura|Analógica|Mide la temperatura interior en °C|
|Sensor de humedad|Analógica|Mide el porcentaje de humedad relativa|
|Botón de modo manual|Digital|Permite al usuario tomar control directo|
|Sensor de Luz |Analógica|Mide la luminosidad interior en lux |
|-|-|-|



## Salidas

|Actuador / Salida|Tipo de señal|Descripción|
|-|-|-|
|Ventilador|Digital|Se activa cuando la temperatura supera el límite|
|Calefactor|Digital|Se activa cuando la temperatura baja del límite|
|Pantalla LCD|Digital|Muestra temperatura, humedad y modo activo|
|LED de alerta|Digital|Parpadea si los valores están fuera del rango|
| Bomba de riego| Digital| Se activa cuando la humedad baja del mínimo|



