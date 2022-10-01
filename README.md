# projectIoT2022

## Integrantes

- Erik Daniel Méndez Enríquez
- Oscar Ivan Pérez Mejía
- Alyne Elizabeth Rojas Gloria
- Andrea Trujillo Azpeitia

## Objetivo general

El proyecto que tenemos planeado tiene como objetivo el crear un dispositivo que nos ayude a conocer o advertir el ambiente en el que nuestra mascota se 
encuentre tanto si estamos con ella como si no fuera asi, esto para poder cuidar mejor de nuestra  mascota y poder preveer alguna acción riesgosa en la que 
se pueda encontrar, ademas de ayudar a nosotros mismo a conocer un poco mejor nuestro ambiente para nuestra propia protección en algunos casos.

## Objetivos especificos

- Cuidar a nuestra mascota para previnir accidentes
- Tener un control en el monitoreo de nuestra mascota
- Poder conocer aspectos de nuestro entorno para tomar medidas preventivas 
- Recibir información del entorno de nuestra mascota

## Tabla de Software Utilizado

| Id | Software           | Versión | Tipo |
|----|--------------------|---------|------|
| 1  | Visual Studio Code | 17.2    | IDE  |
| 2  | Arduino            | 2.0.0   | IDE  |

## Tabla de Hardware utilizado

| Id | Componente                       | Descripción                                                                                                                                                                                                                                                                         | Imagen | Cantidad | Costo Total |
|----|----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|----------|-------------|
| 1  | ESP32                            | El módulo ESP32 es una solución de  Wi-Fi/Bluetooth todo en uno, integrada  y certificada que proporciona no solo  la radio inalámbrica, sino también un  procesador integrado con interfaces para  conectarse con varios periféricos.                                              |    ![image](https://user-images.githubusercontent.com/84553507/193392556-f26cdec7-c08e-45cd-923f-abc6dedb2dd7.png)| 1        | $150.00     |
| 2  | Sensor de  temperatura y humedad | El DHT22 (AM2302) es un sensor digital de  temperatura y humedad relativa de buen  rendimiento y bajo costo. Integra un sensor  capacitivo de humedad y un termistor para  medir el aire circundante, y muestra los  datos mediante una señal digital en el pin de datos.           |     ![image](https://user-images.githubusercontent.com/84553507/193392583-740a1455-afde-43b2-942b-5948ac55d759.png)| 1        | $136.00     |
| 3  | Sensor de gas                    |     Este es un sensor de gas metano propano de  hidrógeno, ideal   para la detección de fugas  de gas en el hogar o en la fábrica. Este sensor puede utilizarse para detectar: Gas combustible  como GLP, butano, metano, alcohol, propano,  hidrógeno, humo.                       |    ![image](https://user-images.githubusercontent.com/84553507/193392596-129cc8e6-de15-483b-9ce1-e5c8ef18ca6d.png)| 1        | $79.50      |
| 4  | Sensor de llama                  | Este sensor detecta la presencia de llama.  Detecta una llama o una fuente de luz de una  longitud de onda en el rango de 760nm-1100 nm.  Una prueba de llama ligera puede ser activada  dentro de 0.8m. Si la intensidad de la llama es  alta, la distancia de detección aumentará |    ![image](https://user-images.githubusercontent.com/84553507/193392606-c821e684-f712-47f9-b891-ad8092361069.png)| 1        | $50.00      |
| 5  | GPS                              | El Sistema de Posicionamiento Global (GPS)  es un sistema que permite localizar cualquier  objeto (una persona, un vehículo, etc) sobre la  Tierra con una precisión de hasta centímetros                                                                                           |     ![image](https://user-images.githubusercontent.com/84553507/193392613-79a78f1d-4d79-410b-89e1-e319334d8e80.png)| 1        | $201.00     |
| 6  | LED                              | Un diodo LED es un dispositivo que permite el  paso de corriente en un solo sentido y que al  ser polarizado emite un haz de luz                                                                                                                                                    |    ![image](https://user-images.githubusercontent.com/84553507/193392617-b7587229-1575-40fc-8a9f-79402a560e38.png)| 3        | $18.00      |
| 7  | Buzzer                           | Un buzzer o zumbador es un dispositivo que es  capaz de enviar avisos a través del sonido. Puede  ser mecánico, electromecánico o piezoeléctrico.                                                                                                                                   |  ![image](https://user-images.githubusercontent.com/84553507/193392627-54c5c576-f5fc-44fc-b7b8-ecce85c0376c.png)| 1        | $71.00      |
| 8  | LCD                              | LCD o pantalla de cristal líquido, está  conformada por un número de píxeles en color  o monocromos colocados delante de una fuente  de luz o reflectora, es delgada y plana.                                                                                                       |     ![image](https://user-images.githubusercontent.com/84553507/193392631-6b05398c-195d-4acb-8c28-13669af5fbde.png)| 1        | $87.00      |
| 9  | Cámara                           | El sensor de imagen OV7670 cuenta con una  cámara VGA de un solo chip y procesador de  imágenes para todas las funciones.                                                                                                                                                           |    ![image](https://user-images.githubusercontent.com/84553507/193392634-ca093ec2-b972-42df-b369-b77f009030c4.png)| 1        | $135.00     |

## Epicas del proyecto
- Quiero poder conocer el ambiente en el que se encuentra mi mascota en caso de que se pierda.
- Quiero poder saber si mi mascota se encuentra en peligro de intoxicación o si el ambiente que lo rodea hay peligro de una fuga de gas
- Quiero conocer si mi mascota corre el riesgo de sufrir algun daño por quemadura mientras no me encuentro con el.
- En caso de perder a mi mascota quiero poder dar con el en tiempo real para ir a buscarlo y alcanzarlo.

## Tabla de historias de usuario

| Id | Historias de Usuario                                                                                                                    | Prioridad | Estimación    | Como probarlo                                                     | Responsable                  |
|----|-----------------------------------------------------------------------------------------------------------------------------------------|-----------|---------------|-------------------------------------------------------------------|------------------------------|
| 1  | Quiero poder conocer el ambiente en el que se encuentra mi mascota  en caso de que se pierda.                                           | Alta      | 3 semanas     | Aumentando temperatura y humedad                                  | Erik Daniel Mendez Enriquez  |
| 2  | Quiero poder saber si mi mascota se encuentra en peligro de intoxicación o si  el ambiente que lo rodea hay peligro de una fuga de gas. | Alta      | 2 a 3 semanas | Usando un gas de manera controlada cerca del sensor               | Oscar Iván Pérez Mejía       |
| 3  | Quiero conocer si mi mascota corre el riesgo de sufrir algún daño por  quemadura mientras no me encuentro con él.                       | Alta      | 3 semanas     | Exponiendo el proyecto a una llama controlada                     | Alyne Elizabeth Rojas Gloria |
| 4  | En caso de perder a mi mascota quiero poder dar con el en tiempo  real para ir a buscarlo y alcanzarlo.                                 | Alta      | 3 semanas     | Desarrollando una aplicación que nos permita probar el sensor GPS | Andrea Trujillo Azpeitia     |

## Boceto

![image](https://user-images.githubusercontent.com/84553507/193392187-23cd387b-3375-468c-8c75-f38fdff7a801.png)
