# TFG_2021-22
En este repositorio esta tanto el código como la memoria que entregue en mi TFG


# Implementación de un sistema de detección de objetos dual en el espectro visible y en el infrarrojo

Actualmente los sistemas de detección y reconocimiento de imágenes automatizados están
generalmente basados en el tratamiento de imágenes obtenidas en el espectro visible. Sin embargo, en
determinadas ocasiones, especialmente en situaciones de baja iluminación o visibilidad, es imposible
obtener imágenes con la suficiente calidad en el espectro visible. En estos casos suele ser posible
conseguir imágenes basadas en el espectro infrarrojo. Desafortunadamente los sistemas más habituales
de reconocimiento de imágenes fallan al reconocer los diferentes objetos en las imágenes cuando estas
son infrarrojas ya que han sido únicamente entrenados con imágenes del espectro visible.
Por otro lado, las bases de datos de imágenes disponibles están, en su mayor parte, compuestas de
imágenes del espectro visible y es difícil conseguir bases de datos de imágenes infrarrojas. Esto dificulta
entrenar nuevos sistemas para reconocer este tipo de imágenes.
Este trabajo tiene como objetivo resolver este problema, desarrollando un sistema dual, capaz de realizar
detección y reconocimiento en las imágenes infrarrojas y al mismo tiempo creando un procedimiento
para automatizar la generación de bases de datos de imágenes térmicas listas para usar como conjuntos
de entrenamiento de nuevos sistemas.
Para ello, se estudiaron diferentes redes neuronales y métodos de adquisición, detección y tratamiento
de imágenes, seleccionando el más conveniente para usar en nuestro sistema.
A continuación, utilizando un dispositivo capaz de captar las imágenes en ambos espectros a la vez, se
generó un conjunto doble de imágenes tanto en el espectro visible como en el infrarrojo. Sobre el
conjunto de imágenes de espectro visible se aplicaron las técnicas de reconocimiento del sistema
elegido, detectando e identificando los objetos de la imagen, así como sus posiciones dentro de la
misma.
Los datos obtenidos de cada imagen se utilizaron para el tratamiento de la misma imagen en el espectro
infrarrojo, generando automáticamente un Conjunto de Datos de entrenamiento que nos permitió
conseguir el objetivo planteado en el proyecto, un nuevo sistema capaz de reconocer, con un alto grado
de fiabilidad, los objetos contenidos en las imágenes infrarrojas.
