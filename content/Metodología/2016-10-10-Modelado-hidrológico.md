---
date: "2019-10-10T21:49:57-07:00"
title: Modelado hidrológico
---
En esta etapa se aplican herramientas de modelado hidrológico para construir la **red de drenaje natural** en la región, una estimación de interés para identificar las principales corrientes superficiales por las que fluye el recurso y los rasgos que definen los parámetros de recarga de los acuíferos, así como factores potenciales de contaminación por el arrastre de sustancias empleadas en la actividad agrícola intensiva como los fertilizantes. 
Para este propósito se emplea como fuente primaria el modelo digital de elevación con resolución de 15 metros por pixel **Continuo de Elevaciones Mexicano**, (INEGI, 2019). Se emplea el software **ILWIS** (Integrated Land and Water Information System), con un análisis en tres fases a partir de imágenes en formato ráster. 
En la primera fase se determinan las pendientes del terreno y su respectiva clasificación en 5 categorías

- [ ] A: Terreno plano con un límite superior en la pendiente de 3 grados 
- [ ] B: terreno ligeramente plano 7°
- [ ] C: terreno ligeramente inclinado 12° 
- [ ] D: terreno inclinado 25°
- [ ] E: terreno muy inclinado con límite superior en la pendiente de 50 grados. 

La segunda fase captura la **dirección de flujo** 

Y en la tercera se determinan las **áreas de captación**.  

En esta fase se obtiene **como producto una cobertura en formato vectorial para la red de drenaje natural en región en la que se ubica el valle**.
