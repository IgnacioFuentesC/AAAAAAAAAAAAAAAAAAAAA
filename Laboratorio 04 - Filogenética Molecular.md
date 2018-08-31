# Laboratorio 04 - Filogenética Molecular [![img](https://github.com/bioinf-biotec/labs_bioinf/raw/master/images/tree.png?raw=true)](https://github.com/bioinf-biotec/labs_bioinf/blob/master/images/tree.png?raw=true)

### Ignacio Fuentes ###


**1.** ¿Qué ofrece o para qué sirve el portal Phylogeny.fr? [2]

**R: Es un servicio dedicado a reconstruir y analizar relaciones filogenéticas entre secuencias moleculares. Además conecta varios programas bioinformáticos para reconstruir árboles filogenénticos a partir de un set de secuencias**

**http://www.phylogeny.fr/index.cgi**

**2.** Nombra y explica brevemente los 3 modos en los que se puede ejecutar el pipeline de Phylogeny.fr. [2]

**R: "One Click mode" se dirige a los usuarios que no desean ocuparse de la selección de programas y parámetros. Por defecto, la canalización ya está configurada para ejecutarse y conectar programas reconocidos por su precisión y velocidad (MUSCLE para alineación múltiple y PhyML para filogenia) para reconstruir un árbol filogenético robusto a partir de un conjunto de secuencias.**

**"Advanced mode", el servidor de Phylogeny.fr propone la sucesión de los mismos programas, pero los usuarios pueden elegir los pasos a realizar (alineación de secuencia múltiple, reconstrucción filogenética, dibujo de árbol) y las opciones de cada programa.**

**"A la carte mode" ofrece la posibilidad de ejecutar y probar más programas de alineación y filogenia, como MUSCLE, ClustalW, T-Coffee, PhyML, BioNJ, TNT.**

**http://www.phylogeny.fr/documentation.cgi**

**3.** Menciona qué tipos de análsis se pueden realizar en el portal de acuerdo a la documentación. (*Online Programs*) [2]

**R: Se puede realizar análisis por búsqueda de secuencias homología de secuencias, múltiple alineamiento, filogenia, visualizadores de árbol, refinamiento de alineamiento, conversión de formato.**

**http://www.phylogeny.fr/programs.cgi**

**4.** Incluye en tu informe una captura de pantalla de las dos filogenias que inferiste. Recuerda que tu nombre completo debe aparecer en la imagen de cada filogenia (*Name of the analysis*). [2]

![filogenia 1](https://github.com/IgnacioFuentesC/AAAAAAAAAAAAAAAAAAAAA/blob/master/filogenia%20n%C3%BAmero%201.JPG?raw=true)

![filogenia 2](https://github.com/IgnacioFuentesC/AAAAAAAAAAAAAAAAAAAAA/blob/master/filogenia%20n%C3%BAmero%202.JPG?raw=true)

**5.** ¿A qué se refiere el paso de *Alignment curation* y para qué sirve? [3]

**R: Se realiza para eliminar el ruido y regiones que se alinean mal. Sirve para realizar un analisis filogenético.**

**6.** ¿Cuál es la diferencia entre BioNJ y Neighbor? [3]

**R: Ambos tienen el mismo fin: Reconstruir filogenias basadas en la distancia. Sin embargo, BioNJ es mejor ya que tiene una mejor precisión topológica en todas las condiciones evolutivas y se vuelve importante cuando las tasas de sustitución son altas y varían entre linajes.**

**7.** Incluye en tu informe una captura de pantalla de las dos filogenias que inferiste (sin *Alignment curation*). Recuerda que tu nombre completo debe aparecer en la imagen de cada filogenia (*Name of the analysis*). [2]

![filogenia 1.2](https://github.com/IgnacioFuentesC/AAAAAAAAAAAAAAAAAAAAA/blob/master/filogenia%201.JPG?raw=true)

![filogenia 2.2](https://github.com/IgnacioFuentesC/AAAAAAAAAAAAAAAAAAAAA/blob/master/filogenia%202.JPG?raw=true)

**8.** ¿Cuál es el efecto de no hacer la curación del alineamiento en las filogenias? [3]

**R: Cambia el orden y la cantidad de grupos monofiléticos, éste último, cuando se realiza alineamiento sin curación tiende a aumentar.**

**9.** Describe las diferencias entre las filogenias que has estimado (4 en total): cantidad de grupos monofiléticos, relaciones que potencialmente cambiaron, etc. [5]

**R: Cuando se realiza alineamientos de filogenias sin curar, tiende a aumentar la cantidad de grupos monofiléticos, por lo que se infiere que, en los casos sin curación hay más especiación que cuando se realiza curación. La primera filogenia pasó de tener 19 a 23 nodos. La segunda filogenia pasó de tener 24 a 27 nodos.**

**Como consecuencia del punto anterior, cambia el orden del árbol, la distribución de los nodos es distinta.**

**Existen relaciones que cambiaron, como por ejemplo *Homo sapiens*, cuando se realiza la filogenia con curación, la especie filogenéticamente más cercana es *Cebus capucinus* en ambos casos, sin embargo, cuando se realiza sin curación, la especie filogenéticamente más cercana varía y no se conserva en ninguna de las dos filogenias sin curar.**

**Cambia la morfolofía del árbol filogenético. El largo de las ramas varía entre filogenias con y sin curar.**

