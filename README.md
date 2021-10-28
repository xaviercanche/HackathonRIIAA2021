# Hackathon RIIAA 2021 "JusticIA para los desaparecidos"

La desaparición forzada de personas es una violación grave a los derechos humanos. Entre 1964 y 1985 (Guerra sucia) el Estado mexicano se enfrentó y reprimió ferozmente a movimientos sociales, líderes de organizaciones político-militares, simpatizantes, familias y comunidades que consideraba como enemigos. Esclarecer el paradero de las víctimas, que hasta el día de hoy continúan desaparecidas, implica la integración y estructuración de la información contenida en miles de archivos institucionales que han sido digitalizados como imágenes. En esta plática se presentarán propuestas de soluciones basadas en Inteligencia Artificial (IA) para el análisis, clasificación y extracción de información de miles de imágenes de documentos de la represión. Esto como parte de los resultados obtenidos en el 1er Hackathon 2021 “Justicia para los desaparecidos” organizado por la  Reunión Internacional de Inteligencia Artificial y sus Aplicaciones (RIIAA). Entre  las actividades que se realizaron  está la detección y extracción de texto de las imágenes, el reconocimiento de caracteres y su semantización, el reconocimiento facial de personas, reconocimiento de firmas y sellos en los documentos. Algunas herramientas utilizadas son el aprendizaje profundo, clustering, visión computacional y procesamiento de lenguaje natural.


## Team:
**Pista Latente ML**

- Andrea Ek
- Gabriela Mundo
- Xavier Canche
- Myrna Castillo
- Ramón Aparicio

# Solution for Challenge 1.
**Pipeline:**
<img src="images/reto1.png" width="800">

**Face recognition:**
Use lib face_recognition with Convolutional Neural Netwok.  
<img src="images/face.png" width="800">

**Segmentation:**
Segmentation with image processing.  
<img src="images/seg.png" width="800">

**Clustering:**
Feature extract with Deep Neural Network VGG16 and clustering with K-means and agglomerative hierarchical clustering.  
<img src="images/cluster.png" width="800">

**Results:**
<img src="images/results.png" width="800">

# Solution for Challenge 2.
**Pipeline:**
<img src="images/reto2.png" width="800">

**Text Segmentation:**
We use same segmentation of challenge 1. 
<img src="images/textseg1.png" width="800">

**Text Recognition:**
We use pytesseract for text recognition on text segmentation.  
<img src="images/textseg2.png" width="800">

**Reference:**
- https://github.com/Hackaton-JusticIA-2021/pista-latente-ML-sol
- https://riiaa.org/
- https://archivosdelarepresion.org/
- https://www.eventbrite.com/e/riiaa-2021-hackathon-justicia-para-los-desaparecidos-tickets-163293237469
- https://www.entrepreneur.com/article/379973

