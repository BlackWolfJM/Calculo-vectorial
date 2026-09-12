# Elipse

Una **elipse** es el conjunto de puntos del plano cuya suma de distancias a dos puntos fijos, llamados focos, permanece constante.

## 1. Formas estándar

### Eje mayor horizontal

$$
\frac{(x-h)^2}{a^2}+\frac{(y-k)^2}{b^2}=1, \qquad a>b>0
$$

### Eje mayor vertical

$$
\frac{(x-h)^2}{b^2}+\frac{(y-k)^2}{a^2}=1, \qquad a>b>0
$$

En ambos casos, $(h,k)$ es el centro y se cumple:

$$c^2=a^2-b^2$$

## 2. Elementos

| Elemento | Horizontal | Vertical |
|---|---|---|
| Centro | $(h,k)$ | $(h,k)$ |
| Vértices | $(h\pm a,k)$ | $(h,k\pm a)$ |
| Co-vértices | $(h,k\pm b)$ | $(h\pm b,k)$ |
| Focos | $(h\pm c,k)$ | $(h,k\pm c)$ |
| Eje mayor | $2a$ | $2a$ |
| Eje menor | $2b$ | $2b$ |

## 3. Excentricidad

$$e=\frac{c}{a}, \qquad 0<e<1$$

Cuanto más cerca esté $e$ de 0, más circular será la elipse. Cuanto más cerca esté de 1, más alargada será.

## 4. Procedimiento para analizar una elipse

1. Llevar la ecuación a la forma estándar.
2. Identificar el centro $(h,k)$.
3. Determinar cuál denominador es mayor: ese valor es $a^2$.
4. Reconocer la orientación del eje mayor.
5. Calcular $a$, $b$ y $c=\sqrt{a^2-b^2}$.
6. Ubicar vértices, co-vértices y focos.
7. Dibujar el rectángulo auxiliar y trazar la elipse.

## 5. Propiedad focal

Para cualquier punto $P$ de la elipse:

$$PF_1+PF_2=2a$$

## Notebook

- [Abrir el notebook de Elipse en GitHub](./elipse.ipynb)
- [Abrir directamente en Google Colab](https://colab.research.google.com/github/BlackWolfJM/Calculo-vectorial/blob/main/01%20-%20C%C3%B3nicas%20en%20coordenadas%20cartesianas/Elipse/elipse.ipynb)
