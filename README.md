El ordenamiento por inserción funciona recorriendo la lista desde el segundo elemento, porque que el primero se considera como que ya esta ordenado. 
en cada vuelta se guarda el elemento y lo compara con los elementos que tiene a su izquierda.
si alguno de los elementos anteriores es mas grande que el actual, se va moviendo una posición a la derecha.
este proceso sigue hasta encontrar la posición para el elemento 
y asi poco a poco la parte de la izquierda de la lista se va ordenando hasta que se queda ordenada del todo 

la complejidad depende de como este la lista al principio, si ya esta ordenada solo hace falta recorrerla una vez, entonces el mejor caso es Ω(n)
si est aordenada al reves, cada elemento tendrá que compararse con el anteorior entonces daría un peor caso de O(n²). 
