El propósito del primer coddigo es restar tres números enteros de 16 bits (num1, num2, num3) y mostrar el resultado como un carácter ASCII en la consola. Primero, se realiza la resta de los tres números y se almacena el resultado en la variable result. Luego, se muestra un mensaje en la consola y se convierte el resultado a su representación ASCII (asumiendo que el resultado es un número de un solo dígito) antes de mostrarlo en la consola.

El siguiente codigo ensamblador realiza la multiplicación de dos números de 8 bits (num1 y num2) y luego imprime el resultado como un número decimal en la consola.
Los números se cargan en los registros AL y BL.
Se utiliza la instrucción mul para multiplicar AL (el primer número) por BL (el segundo número).
El resultado se guarda en la variable result.
Se llama a la función print_num para imprimir el resultado en la consola.
La función print_num convierte el número a su representación decimal (ASCII) y lo imprime en la consola.
Al finalizar, el programa sale con el código de salida 0.

Este ultimo código en ensamblador realiza la división de dos números enteros de 32 bits (dividend y divisor) ingresados por el usuario y muestra el resultado en la consola.
Solicita al usuario que ingrese el dividendo y el divisor.
Lee la entrada del usuario para el dividendo y el divisor.
Realiza la división de los números.
Guarda el resultado de la división en la variable result.
Imprime un mensaje indicando el resultado de la división.
Llama a la función print_int para imprimir el resultado como un número entero sin signo.
