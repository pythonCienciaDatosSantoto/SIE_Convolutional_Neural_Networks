# Introducción a la Visión por Computador (Computer Vision)

## ¿Qué es la Visión por Computador?

La Visión por Computador es un campo de la inteligencia artificial (IA) y de las ciencias de la computación que busca permitir que las computadoras y los sistemas "vean", interpreten y comprendan el mundo visual. Utilizando imágenes digitales de cámaras y videos, así como modelos de aprendizaje profundo, las máquinas pueden identificar y localizar objetos con precisión, y luego reaccionar a lo que "ven".

En esencia, el objetivo es enseñar a las máquinas a percibir el mundo de una manera similar a como lo hacen los humanos.

"El gran objetivo de la Visión por Computador es hacer que los computadores entiendan las imágenes y los videos al nivel de un humano."

— Fei-Fei Li, Profesora de la Universidad de Stanford y pionera en IA.

## Un Breve Recorrido Histórico

La idea de dar vista a las máquinas no es nueva, pero el campo ha experimentado una explosión de avances en la última década gracias al Deep Learning.

+ Los Inicios (1960s-1980s): Los primeros intentos se centraron en extraer características simples como bordes y esquinas mediante algoritmos manuales. Un trabajo pionero fue el Neocognitron (Fukushima, 1980), una de las primeras arquitecturas neuronales jerárquicas inspirada en la corteza visual humana, sentando las bases para las futuras CNNs.

+ Las Primeras CNNs (1990s): Yann LeCun et al. desarrollaron LeNet-5 en 1998, una de las primeras Redes Neuronales Convolucionales exitosas, que demostró un rendimiento excepcional en el reconocimiento de dígitos manuscritos. Este fue un hito que probó la viabilidad de las CNNs para tareas de reconocimiento de patrones.

+ La Revolución del Deep Learning (2012-Presente): El punto de inflexión llegó en 2012 con la competencia ImageNet (ILSVRC). La arquitectura AlexNet (Krizhevsky et al.) redujo drásticamente la tasa de error y demostró la superioridad de las CNNs profundas entrenadas en GPUs. A partir de ahí, surgieron arquitecturas cada vez más sofisticadas que siguieron rompiendo récords:

VGGNet (2014): Demostró que la profundidad de la red era un factor crítico.

GoogLeNet / Inception (2014): Introdujo módulos "Inception" para una mayor eficiencia computacional.

ResNet (2015): Introdujo las "conexiones residuales" para permitir el entrenamiento de redes extremadamente profundas (más de 150 capas) sin problemas de desvanecimiento de gradiente.

## Tareas Fundamentales en Visión por Computador

La Visión por Computador abarca una variedad de tareas, desde las más simples hasta las más complejas:

+ Clasificación de Imágenes: La tarea más básica. El objetivo es asignar una etiqueta a una imagen completa. (Ej: "Esta imagen contiene un perro").

+ Localización de Objetos: Además de clasificar, se dibuja un cuadro delimitador (bounding box) alrededor de la instancia del objeto.

+ Detección de Objetos: Es la localización de múltiples objetos en una misma imagen. Es la tarea que abordamos con R-CNN y YOLO.

+ Segmentación de Imágenes: La tarea más granular. El objetivo es clasificar cada píxel de la imagen, creando una máscara precisa para cada objeto.

## Referencias y Recursos Adicionales

Para aquellos interesados en profundizar, aquí hay una lista de recursos clave.

Artículos Científicos (Papers) Clave

+ Neocognitron: Fukushima, K. (1980). Neocognitron: A self-organizing neural network model for a mechanism of pattern recognition unaffected by shift in position. [Link al paper:](https://www.cs.princeton.edu/courses/archive/spr08/cos598B/Readings/Fukushima1980.pdf)

+ LeNet-5: LeCun, Y., Bottou, L., Bengio, Y., & Haffner, P. (2002). Gradient-based learning applied to document recognition. [Link al paper:](https://hal.science/hal-03926082/document)

+ AlexNet: Krizhevsky, A., Sutskever, I., & Hinton, G. E. (2012). ImageNet classification with deep convolutional neural networks. [Link al paper:](https://proceedings.neurips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf)

+ VGGNet: Simonyan, K., & Zisserman, A. (2014). Very deep convolutional networks for large-scale image recognition. [Link al paper:](https://arxiv.org/pdf/1409.1556)

+ GoogLeNet: Szegedy, C., Liu, W., Jia, Y., Sermanet, P., Reed, S., Anguelov, D. & Rabinovich, A. (2015). Going deeper with convolutions. [Link al paper:](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Szegedy_Going_Deeper_With_2015_CVPR_paper.pdf)

+ ResNet: He, K., Zhang, X., Ren, S., & Sun, J. (2016). Deep residual learning for image recognition. [Link al paper:](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

+ Petersen, P., & Zech, J. (2024). Mathematical theory of deep learning. arXiv preprint arXiv:2407.18384. [Link al paper](https://arxiv.org/pdf/2407.18384)

Libros Recomendados
"Deep Learning with Python" por François Chollet (creador de Keras). Excelente para una introducción práctica.

"Computer Vision: Algorithms and Applications" por Richard Szeliski. Un texto clásico y completo sobre los fundamentos.