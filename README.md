# ComprobarNotas
Este programa en Java realiza un análisis estadístico básico sobre una colección de calificaciones (números enteros). El objetivo es identificar el rendimiento académico determinando la nota más alta, su frecuencia y el promedio general.
# Funcionalidades
El programa ejecuta las siguientes tareas automáticamente:Búsqueda del máximo: Identifica cuál es la calificación más alta dentro del array.Recuento de frecuencia: Determina si la nota mayor se repite a lo largo de la colección.Cálculo de suma: Acumula el valor total de todas las notas.Cálculo de media: Obtiene el promedio decimal de las calificaciones.Estado académico: Determina si el resultado es APROBADO (media $\ge 5$) o REPROBADO (media $< 5$).
# Estructura del Código
El programa utiliza una lógica sencilla dividida en bloques:
Bucle de comparación: Para encontrar el numMayor y gestionar el contador.
Bucle de suma: Para calcular el total de los puntos antes de dividir por la longitud del array.
Condicionales de salida: Para imprimir los mensajes personalizados en la consola.
# Tecnologías utilizadas
Lenguaje: Java 8 o superior.
Paradigma: Programación imperativa.
# Ejemplo de Uso
Si el array contiene las notas {5, 7, 3, 7, 2, 9, 7}, la salida por consola será:
```java
El número mayor es 9 y no aparece más de una vez en el array.
5.714285714285714
APROBADO
```
# Cómo ejecutarlo
Asegúrate de tener instalado el JDK.
Guarda el archivo como ComprobarNotas.java.
Compila y ejecuta.
