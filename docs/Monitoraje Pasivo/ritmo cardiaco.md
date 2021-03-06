# Actividad cardiaca

La actividad cardiaca permite la detección de la frecuencia de los latidos del corazón. Aunque se usan dos tipos de sensores para detectar la frecuencia cardiaca en ambos se observa los R-R intervalos. Este intervalo marca el punto de expansión del corazón y muestra el intervalo entre latido i latido.

La frecuencia cardiaca varia entre usuarios por muchos factores como: estado fisco, psicológico, edad o afecciones medicas. El sensor debe observar las diferencias en el tiempo, los valores absolutos ofrecen poca información emocional.

Hay que tener cuidado con intentar observar con estos sensores afecciones del corazón como arritmia a causa que en muchas ocasiones durante el proceso de eliminar el ruido de la captura estas irregularidades pueden pasar desapercibidas. En todos los casos es recomendable conocer si el propio sensor ejerce algún tipo de procesamiento a la captura.


<figure markdown>
   ![R-R interval](assets\R-R interval.png)
  <figcaption></figcaption>
</figure>

## Electrocardiograma

El electrocardiograma función observado los impulsos eléctricos que emite el corazón al latir. Este sensor se coloca un electrodo en la piel con el que detecta las diferencias eléctricas.

* Para mejorar la muestra se recomienda el uso de gel conductor y reducir el bello corporal en la posición del electrodo.
* Para calcular el ritmo cardiaco se debe ser la formula:

$$
\operatorname{HRV} =300/(T.R-R)
$$

![2022-06-15 19_05_04-memoria final.docx - Word](assets\2022-06-15 19_05_04-memoria final.docx - Word.png)


| Nombre del sensor                           | Descripción                                                  | Precio | Link                                                         |
| ------------------------------------------- | ------------------------------------------------------------ | ------ | ------------------------------------------------------------ |
| BIOSIGNALPLUX ECG sensor                    | Captura bajo en ruido. La suite de el sensor es completa y tiene integración con otros sensores de la misma marca. | ≈145€  | [BIOSIGNALPLUX ECG](https://www.pluxbiosignals.com/products/electrocardiography-ecg-sensor-1?variant=40878955200703) |
| SEEQ™ sensor                                | Portable, batera de larga duración. Sensor dirigido a la deteccion de enfermedades como tacquicardia. Alta precision. | N/A    | DOI: [10.1109/EMBC.2015.7318785](https://doi.org/10.1109/embc.2015.7318785) |
| ZIO® XT Patch by iRhythm Technologies, Inc. | Se aplica como un parche en el pecho del paciente. Es muy poco invasivo. Mediacal grade. Monitoreo continuo durante 14 dias. | ≈361€  |                                                              |
| wearable biosensor by Philips BX100         | Integración con distintos servicios medicas para sincronización de datos de los pacientes | N/A    |                                                              |
| Arduino ver                                 | Peor detección y requiere de una integración propia. Perfecto para pequeños proyectos y prototipos. | 20€    | https://how2electronics.com/ecg-monitoring-with-ad8232-ecg-sensor-arduino/ |

**Study:**

*A. Rashkovska, M. Depolli, I. Tomašić, V. Avbelj, y R. Trobec, «Medical-Grade ECG Sensor for Long-Term Monitoring», Sensors, vol. 20, n.º 6. MDPI AG, p. 1695, mar. 18, 2020. doi: 10.3390/s20061695.*

**In depth guide to ECG:**

*M. A. Hasnul, N. A. Ab. Aziz, S. Alelyani, M. Mohana, y A. Abd. Aziz, «Electrocardiogram-Based Emotion Recognition Systems and Their Applications in Healthcare—A Review», Sensors, vol. 21, n.º 15. MDPI AG, p. 5015, jul. 23, 2021. doi: 10.3390/s21155015.*

## Fotopletismografia

La fotopletismografía tiene la capacidad de detectar el volumen en sangre de la zona superficial de la piel. El funcionamiento del fotopletismógrafo no requiere de gel ni electrodos, sino que se coloca en zonas con alta densidad de capilares sanguíneos con una pinza. El sistema funciona a través de la emisión de luz verde o roja en la piel, esta señal es captada al rebotar con los capilares obteniendo la onda reflectante. Esta onda es convertida para obtener los cambios en la constricción de los capilares con los latidos. La onda de reflectante también se puede usar para obtener la densidad de oxígeno en sangre.

<figure markdown>
   ![fotopletismografia](assets\fotopletismografia.jpg)
  <figcaption></figcaption>
</figure>
La fotopetismografía es actualmente uno de los sensores más utilizados en *wearables* a causa de un coste bajo y su portabilidad. Aun así, con excepción de algunos *wearables* especializados, la captura de datos está limitada a capturas cortas debido a su formato. Aunque no tienen la mejor fiabilidad, es una herramienta muy accesible.

