Repositorio con los algoritmos de las tres calculadoras solicitadas por la empresa MathTech.
Tutor: ERASTO CUEVAS REYES

Alumno: Ismael Vidaca Gonzalez


 Contenido

| Archivo | Descripción |
|---|---|
| `NombreApellido_A1.pdf` | Documento de la actividad en formato APA |
| `primos.txt` | Algoritmo que identifica si un número es primo |
| `par_impar.txt` | Algoritmo que clasifica 10 números como pares o impares |
| `al_reves.txt` | Algoritmo que invierte un número de 4 dígitos |

 Próximas etapas

- Diagramas de flujo (Actividad 2)
- Código en lenguaje C (Proyecto final)

ALGORITMO: NÚMEROS PRIMOS

1. Inicio.
2. Pedir al usuario un número entero y guardarlo en n.
3. Si n <= 1, imprimir "El número n no es primo" y terminar.
4. Asignar i = 2.
5. Mientras i < n, repetir:
   a) Si n es divisible entre i (el residuo de n ÷ i es 0), imprimir "El número n no es primo" y terminar.
   b) Sumar 1 a i.
6. Imprimir "El número n sí es primo".
7. Fin.

8. ALGORITMO: NÚMEROS PARES E IMPARES

1. Inicio.
2. Asignar contador = 1.
3. Mientras contador <= 10, repetir:
   a) Pedir al usuario un número entero y guardarlo en n.
   b) Si el residuo de n ÷ 2 es 0, imprimir "El número n es par"; en caso contrario, imprimir "El número n es impar".
   c) Sumar 1 a contador.
4. Fin.

ALGORITMO: NÚMEROS INVERTIDOS

1. Inicio.
2. Pedir al usuario un número entero de 4 dígitos y guardarlo en n.
3. Si n < 1000 o n > 9999, mostrar un mensaje de error y regresar al paso 2.
4. Calcular d1 = n ÷ 1000 (división entera).
5. Calcular d2 = (n ÷ 100, división entera) y obtener el residuo entre 10.
6. Calcular d3 = (n ÷ 10, división entera) y obtener el residuo entre 10.
7. Calcular d4 = residuo de n ÷ 10.
8. Calcular invertido = (d4 × 1000) + (d3 × 100) + (d2 × 10) + d1.
9. Imprimir invertido.
10. Fin.
