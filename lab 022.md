#Laboratorio 02 - Alineamiento de secuencias
---
##Parte 1: Colectar genes homólogos
#####1. ¿Qué función cumple el gen SRY?
R: El gen SRY codifica un factor de transcripción que es un miembro de la familia de proteínas de unión a ADN del grupo de alta movilidad (HMG).
#####2. ¿Cuántos genes ortólogos están anotados en esa base de datos?
R: 29 genes ortólogos en la base de datos.
##Parte 2: Alineamiento múltiple
#####3. ¿Qué es el EMBL-EBI?
R: Es el Instituto Europeo de Bioinformática (EMBL-EBI) un centro de investigacion sin fines de lucro. 
#####4. ¿Cuál es el programa que ellos ofrecen que funciona mejor para secuencias de proteínas?
R: El programa MUSCLE funciona mejor para proteinas.
#####5. ¿Qué otros tipo de herramientas ofrece EMBL-EBI?
R: Herramientas que utiliza árboles de guía sembrados y técnicas de perfil de perfil HMM para generar alineaciones. Herramienta MSA que se concentra en las regiones locales para grandes alineaciones. Herramienta MSA que usa transformadas rápidas de Fourier. Adecuado para alineaciones medianas y grandes. Transformar un resultado de Búsqueda de similitud de secuencia en una Alineación de secuencia múltiple o formatear una Alineación de secuencia múltiple. Herramienta MSA basada en intenta mitigar los riesgos de los métodos de alineación progresiva. Adecuado para pequeñas alineaciones. Herramientas de alineamiento de secuencia múltiple que tiene en cuenta la filogenia y hace uso de información evolutiva para ayudar a colocar inserciones y eliminaciones. 
#####6. ¿Cuál es el costo de abrir un gap?
R: El costo de abrir un gap es de 1.53 
#####7. ¿Cuál es el costo de extender un gap?
R: El costo de extender un gap es de 0.123
#####8. ¿Cuál es la longitud total del alineamiento?
R: La longitud total es de 1934 pb.
#####9. ¿Cuál es la especie cuyo gen SRY está más relacionado con el gen SRY de humanos?
R: SRY_Piliocolobus_tephrosceles 0.00129 
#####10. ¿Cuál es el más lejano?
R: SRY_Desmodus_rotundus 0.0973 
#####11. ¿Cuál es la especie cuyo gen SRY es más cercana a la del burro?
R: Equus_przewalskii
#####12. ¿Cómo esperas que sea el alineamiento si el costo de abrir un gap aumenta? ¿Y si disminuye?
R: Al abrir un gap y si el costo aumenta, el alineamiento aumenta el largo de la secuencia y si diminuye el costo de abrir un gap, el alineamiento aumenta aún más ya que las secuencias tienden a emparejarse.
#####13. ¿Cómo esperas que sea el alineamiento si el costo de extender un gap aumenta? ¿Y si disminuye?
R: Si aumenta el costo de extender un gap disminuye el largo de la secuencia ya que se pierden nucleotidos, y si disminuye el costo, la secuencia aumenta ya que se alinean los nucleotidos. 
#####14. ¿Cuál fue el efecto de aumentar el costo de abrir un gap en la longitud total del alineamiento?
R: El efecto fue que la longitud total de alineamiento disminuyó a 1895 pb   
#####15. Prueba lo mismo, pero esta vez disminuyendo al mínimo el costo de extender un gap. Describe cómo cambia el alineamiento. 
R: Al disminuir al mínimo el costo de extender un gap, aumenta la longitud de la secuencia ya que se suman más nucleotidos alineados y esta aumenta a 1953 pb.
##Parte 3: Diseño de partidores
#####16. Agrega a tu informe una lista de los "LEFT PRIMER" y "RIGHT PRIMER" que obtuviste usando Primer3.
R: LEFT PRIMER: TTACAGGCCATGCACAGAGA ; GGATAGAGTGAAGCGACCCA ; AGATGCTGCCGAAGAATTGC ; CGAAGATGCTGCCGAAGAAT 

   RIGHT PRIMER: CTTGAGTGTGTGGCTTTCGT ; TTTCTCTCTGTGCATGGCCT ; GCTTTGTCCAGTGGCTGTAG ; CTACAGCTTTGTCCAGTGGC 
#####17. Indica los partidores forward y reverse que escogiste y explica por qué son la mejor opción para amplificar el gen SRY de humano.
R: El partidor foward que elegi es el Pr0003 y el reverse es el Pr0008, trabaje con estos partidores porque tienen un mayor porcentaje GC y combinados dan un mayor tamaño de fragmento amplificado. 
#####18. ¿Cuál es el largo del amplicón? ¿Y la temperatura de annealing sugerida?
R: El largo del amplicón es de 445 y la temperatura es de 57,1.