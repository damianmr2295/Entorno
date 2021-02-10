**Tarea 5: Depuración de un programa**

**1. Explicar QUÉ HACE EL MÉTODO MAIN.**

Primero declara dos arrays con un tamaño de 10. Luego rellena los arrays con numeros aleatorios y muestra el primer array, ordena el array por valor de más pequeño a más grande y lo vuelve a mostrar ya ordenado y te dice cuanto ha tardado en ordenarlo. 

Una vez terminado con el primer array muestra el segundo desordenado, lo ordena y lo muestra  y te dice cuanto ha tardado en ordenarlo.

**2. Poner un punto de ruptura (breakpoint) en la línea 78 (primer bucle del método intercambio) y, basándoos en los valores que van tomando las variables, explicad cómo funciona el método de ordenación de arrays por intercambio. Podéis crear tablas para ver cómo cambian los valores de los arrays**

Compara el valor de "lista[i]" al valor de "lista[j]", si el valor de "lista[i]" es mas pequeño, "lista[j]" sumará 1 y volverán a compararse, si el valor de "lista[j]" es más pequeño se intercambian los valores, la posición de "lista[j]" sumará 1 y se volverán a comparar. "lista[j]" da una vuelta al bucle desde la posición "lista[i]" hasta la ultima posición (en este caso 10), La posición de "lista[j]" siempre será igual o mayor que la posción de "lista[i]". En cada posición que suma "lista[j]" se comparan los valores, cuando este acaba, la posición "lista[i]" suma 1 y se vuelve a repetir el proceso.

**3. Poner un punto de ruptura (breakpoint) en la línea 94 y explicad cómo funciona el método de ordenación de arrays de conteo. Podéis crear tablas para ver cómo cambian los valores de los arrays.**

Crea un array de tamaño 101 ((max = 100) - (min = 0) +1) donde coloca con un 1 todos los valores del array "lista[]" en la posición que sea igual a su valor y el resto de posiciones con un 0. Luego corre el array de la posición 0 a la 100 y donde tenga el valor 1 le pasará su posición como valor a array[z] (si su posición es 46 en array[z] se introducirá 46) .
