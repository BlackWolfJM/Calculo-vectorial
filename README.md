# 📐 Geometría Analítica y Cálculo Vectorial con Python

Este repositorio contiene implementaciones en Python de conceptos fundamentales de **geometría analítica** y **cálculo vectorial**, desarrollados como parte del aprendizaje en clase.

Los programas están diseñados para ejecutarse en **Google Colab** y combinan teoría matemática con visualización gráfica usando librerías como `NumPy` y `Matplotlib`.

---

## 📂 Contenido del repositorio

### 🔵 Sección: Cónicas

* 📍 **Elipse**

  * Cálculo de centro, focos y excentricidad
  * Representación gráfica
  * Implementación con clases en Python

# 📘 Teoría de la Elipse

## 🔷 1. Definición
Una **elipse** es el conjunto de puntos en el plano tales que:

> La suma de las distancias a dos puntos fijos llamados **focos** es constante.

---

## 🔷 2. Elementos de la elipse

- **Centro (C):** punto medio entre los focos  
- **Focos (F₁, F₂):** puntos fijos dentro de la elipse  
- **Eje mayor:** segmento más largo de la elipse  
- **Eje menor:** segmento perpendicular al eje mayor  
- **Semieje mayor (a):** mitad del eje mayor  
- **Semieje menor (b):** mitad del eje menor  
- **Distancia focal (c):** distancia del centro a cada foco  

---

## 🔷 3. Relación fundamental

$$
c^2 = a^2 - b^2
$$

---

## 🔷 4. Ecuación de la elipse

### ✔️ Forma estándar (centro en el origen)

### Horizontal:
$$
\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1
$$

### Vertical:
$$
\frac{x^2}{b^2} + \frac{y^2}{a^2} = 1
$$

---

## 🔷 5. Ecuación con centro desplazado

### Horizontal:
$$
\frac{(x - h)^2}{a^2} + \frac{(y - k)^2}{b^2} = 1
$$

### Vertical:
$$
\frac{(x - h)^2}{b^2} + \frac{(y - k)^2}{a^2} = 1
$$

Donde:
- $(h, k)$ es el centro

---

## 🔷 6. Coordenadas importantes

### ✔️ Eje horizontal:
- Focos: $(\pm c, 0)$
- Vértices: $(\pm a, 0)$

### ✔️ Eje vertical:
- Focos: $(0, \pm c)$
- Vértices: $(0, \pm a)$

---

## 🔷 7. Excentricidad

$$
e = \frac{c}{a}
$$

- $0 < e < 1$
- Mientras más cerca de 0 → más circular  
- Mientras más cerca de 1 → más alargada  

---

## 🔷 8. Longitud de los ejes

- Eje mayor: $2a$  
- Eje menor: $2b$  

---

## 🔷 9. Aplicaciones

- Órbitas planetarias  
- Óptica (reflexión de la luz)  
- Ingeniería y diseño  
- Arquitectura  

---

## 🔷 10. Propiedad importante

> La suma de distancias desde cualquier punto de la elipse a los focos es constante:

$$
d_1 + d_2 = 2a
$$


---

## ⚙️ Tecnologías utilizadas

* Python 3
* NumPy
* Matplotlib
* Google Colab
---

## 🎯 Objetivo del proyecto

Aplicar conceptos matemáticos mediante programación para:

* reforzar el aprendizaje teórico
* visualizar estructuras geométricas
* desarrollar habilidades en Python

---

## 📌 Estado del proyecto

🚧 En desarrollo — se irán agregando más temas y mejoras progresivamente.

---

## 👨‍💻 Autor

Proyecto desarrollado como parte de estudios en matemática y programación.
Todo el código ha sido implementado íntegramente por mí como parte del proceso de aprendizaje y práctica.

---

## 📎 Notas

Todos los notebooks están pensados para ejecutarse en:
👉 https://colab.research.google.com/

---



