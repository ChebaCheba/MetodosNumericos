
# Newton Raphson No Lineal
 
Una variante del método Newton Raphson, pero para matrices. Sirve exactamente para lo mismo, solamente que ahora agrega una variante a su fórmula para funcionar en matrices. Como no hay división de matrices, se utiliza la matriz inversa de la matriz Jacobiana, que consiste en una matriz de la derivadas respecto a las variables de cada ecuación. La fórmula es así:

[xr]=[x0]-inv(Jacobi(A[x0]))*A[x0]
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTM2OTYzNzU5N119
-->