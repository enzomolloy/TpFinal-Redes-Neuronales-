# TpFinal-Redes-Neuronales
Trabajo practico sobre red neuronal implementada en Keras utilizando Tensorflow 

Hehco por: Enzo VM, Bautista G, Mateo P.

Conclusion

Para finalizar, esta red neuronal está entrenada para aprender como identificar números escritos a mano descargados de un dataset. El algoritmo aprende a reconocer patrones en las imágenes que le enviamos, en nuestro ejemplo lo que hace es separar la imagen en varias secciones por formas y dependiendo de cada forma, se activa cierta neurona la cual activa la siguiente y despues activa el output con cierto porcentaje. El que tenga el porcentaje de acierto más alto es el correcto. En resumen, se podria decir que nuestra red neuronal funciona como una función enorme, la cual recibe un cierto input, lo procesa y devuelve un output.  
En terminos mas especificos, lo que hacemos es conocido como backpropagation, el cual de manera muy simplificada, es una forma de enseñarle a nuestra red neuronal a aprender. Consiste en introducirle cientos de datos, en nuestro ejemplo, le introducimos imagenes con números escritos a mano. Al final, mediante el backpropagation, le estamos enseñando a nuestra red neuronal a identificar estos patrones. Es algo que vimos en clase, sobre detectar la culpa de posibles errores, por parte de los nodos.
