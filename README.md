# Coeficientes de Clebsch–Gordan

Este repositorio presenta el cálculo de los coeficientes de Clebsch–Gordan mediante un notebook de Wolfram Mathematica, acompañado de un documento PDF que explica su fundamento matemático.

Los coeficientes de Clebsch–Gordan permiten expresar los estados de momento angular total definido en términos de los estados individuales de dos momentos angulares. Describen el cambio entre la base producto |j₁,m₁⟩⊗|j₂,m₂⟩ y la base acoplada |J,M⟩.

El procedimiento construye los operadores de momento angular en el espacio producto y obtiene los estados acoplados mediante diagonalización y aplicación del operador de descenso. Las fases se fijan siguiendo la convención de Condon–Shortley para facilitar la comparación con tablas de referencia.

El ejemplo desarrollado corresponde a j₁=2 y j₂=((1)/(2)), aunque el cálculo permite modificar ambos valores.

## Contenido

- ClebschGordan.nb: notebook con la construcción de los operadores, el cálculo de los coeficientes y la presentación de los estados acoplados.
- ClebschGordan.pdf: explicación breve de los conceptos y del método matemático.
- Coeficientes de Clebsch-Gordan.pdf: tabla de referencia para comparar los resultados.

## Uso

Abre ClebschGordan.nb en Wolfram Mathematica y ejecuta las celdas en orden. Para estudiar otra combinación de momentos angulares, modifica j1 y j2 usando valores enteros o semienteros no negativos y expresiones exactas, como 1/2 o 3/2.

Se emplean unidades en las que ℏ=1.
