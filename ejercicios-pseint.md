# Ejercicios de lógica y PSeInt

## Ejercicio 1: Promedio de tres calificaciones
**Enunciado:** Leer tres calificaciones, calcular y mostrar el promedio aritmético.

**Pseudocódigo:**
```pseudocode
Algoritmo PromedioTresNotas
    Definir n1, n2, n3, promedio Como Real
    Escribir "Ingrese la primera nota:"
    Leer n1
    Escribir "Ingrese la segunda nota:"
    Leer n2
    Escribir "Ingrese la tercera nota:"
    Leer n3
    promedio <- (n1 + n2 + n3) / 3
    Escribir "Promedio: ", promedio
FinAlgoritmo
```

## Ejercicio 2: Número par o impar
**Enunciado:** Leer un número entero e indicar si es par o impar.

```pseudocode
Algoritmo ParOImpar
    Definir numero Como Entero
    Escribir "Ingrese un numero entero:"
    Leer numero
    Si numero MOD 2 = 0 Entonces
        Escribir "El numero es par"
    SiNo
        Escribir "El numero es impar"
    FinSi
FinAlgoritmo
```

## Ejercicio 3: Contar del 1 al 10
```pseudocode
Algoritmo ContarDelUnoAlDiez
    Definir i Como Entero
    Para i <- 1 Hasta 10 Hacer
        Escribir i
    FinPara
FinAlgoritmo
```

## Casos de prueba sugeridos
| Ejercicio | Entrada | Resultado esperado |
|---|---|---|
| Promedio | 80, 90, 100 | 90 |
| Par/impar | 8 | Par |
| Par/impar | 7 | Impar |
| Conteo | Sin entrada | Números del 1 al 10 |

## Actividades pendientes
- [ ] Crear un algoritmo que calcule el área de un triángulo.
- [ ] Crear una calculadora de cuatro operaciones con control de división entre cero.
- [ ] Determinar el mayor de cuatro números.
- [ ] Validar entradas y documentar pruebas.

## Reflexión
[Explica qué estructuras utilizaste, cómo verificaste los resultados y qué mejorarías.]
