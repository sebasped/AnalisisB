---
title: 01 - Cónicas
---

# Curvas cónicas

Las **curvas cónicas** son curvas obtenidas al intersectar un plano con un cono. También pueden estudiarse mediante sus ecuaciones de segundo grado en el plano.

## Objetivos

Al finalizar esta guía deberías poder:

- Reconocer el tipo de cónica a partir de su ecuación.
- Obtener la forma canónica mediante completación de cuadrados.
- Identificar sus elementos geométricos.
- Realizar un bosquejo de la gráfica.
- Relacionar cada cónica con aplicaciones en ingeniería.

---

## Clasificación de las cónicas

| Curva | Forma | Aplicaciones |
|-------|------|--------------|
| Circunferencia | ○ | Ruedas, poleas, engranajes |
| Parábola | ∪ | Antenas, reflectores, trayectorias |
| Elipse | ⬭ | Órbitas, acústica, mecanismos |
| Hipérbola | )( | GPS, radioastronomía, estructuras |

---

## Reconocimiento a partir de la ecuación

La ecuación general de una cónica es

$$
Ax^2+Bxy+Cy^2+Dx+Ey+F=0.
$$

Si no aparece el término \(xy\), el reconocimiento es sencillo.

| Condición | Cónica |
|-----------|---------|
| \(A=C\) | Circunferencia |
| Uno de los términos cuadrados desaparece | Parábola |
| \(A\) y \(C\) tienen el mismo signo pero distinto valor | Elipse |
| \(A\) y \(C\) tienen signos opuestos | Hipérbola |

---

# Circunferencia

## Idea central

La **circunferencia** es el conjunto de todos los puntos del plano que se encuentran a una **distancia constante** de un punto fijo llamado **centro**.

## Ecuación canónica

$$
(x-h)^2+(y-k)^2=r^2
$$

## Elementos

- Centro

$$
C=(h,k)
$$

- Radio

$$
r
$$

La distancia entre el centro y cualquier punto de la circunferencia es siempre igual al radio.

## Procedimiento

1. Completar cuadrados.
2. Hallar el centro.
3. Calcular el radio.
4. Graficar.

## Ejemplo

Determinar centro y radio de

$$
25x^2+25y^2+30x-20y-62=0.
$$

Dividiendo por 25,

$$
x^2+y^2+\frac65x-\frac45y-\frac{62}{25}=0.
$$

Completando cuadrados,

$$
\left(x+\frac35\right)^2+
\left(y-\frac25\right)^2=4.
$$

Por lo tanto,

Centro

$$
\left(-\frac35,\frac25\right)
$$

Radio

$$
r=2.
$$

:::{important}
Todos los puntos de la circunferencia están a una distancia \(r\) del centro.
:::

## Aplicaciones

- Poleas.
- Engranajes.
- Rodamientos.
- Tanques cilíndricos.
- Ruedas.

---

# Parábola

## Idea central

La **parábola** es el conjunto de puntos cuya **distancia al foco** es igual a su **distancia a una recta fija llamada directriz**.

## Ecuación canónica

Vertical

$$
(x-h)^2=4p(y-k)
$$

Horizontal

$$
(y-k)^2=4p(x-h)
$$

## Elementos

- Vértice.
- Foco.
- Directriz.
- Eje de simetría.

El parámetro \(p\) representa la distancia entre el vértice y el foco.

## Ejemplo

Resolver

$$
y^2-6y-4x+5=0.
$$

Completando cuadrados,

$$
(y-3)^2=4(x+1).
$$

Comparando con

$$
(y-k)^2=4p(x-h),
$$

se obtiene

Vértice

$$
(-1,3)
$$

Parámetro

$$
p=1
$$

Foco

$$
(0,3)
$$

Directriz

$$
x=-2.
$$

## Aplicaciones

- Antenas parabólicas.
- Faros de automóviles.
- Telescopios.
- Concentradores solares.
- Trayectorias de proyectiles.

---

# Elipse

## Idea central

La **elipse** es el conjunto de puntos cuya **suma de las distancias a dos puntos fijos**, llamados **focos**, permanece constante.

## Ecuación canónica

Horizontal

$$
\frac{(x-h)^2}{a^2}+
\frac{(y-k)^2}{b^2}=1
$$

con

$$
a>b.
$$

Vertical

$$
\frac{(x-h)^2}{b^2}+
\frac{(y-k)^2}{a^2}=1.
$$

## Elementos

- Centro.
- Semieje mayor \(a\).
- Semieje menor \(b\).
- Vértices.
- Focos.

Los focos se encuentran sobre el eje mayor.

La distancia entre el centro y cada foco es

$$
c^2=a^2-b^2.
$$

Como \(a>b\),

$$
0<c<a,
$$

por lo que los focos siempre quedan **dentro de la elipse**.

### Coordenadas de los focos

Si el eje mayor es horizontal,

$$
F_1=(h-c,k),
\qquad
F_2=(h+c,k).
$$

```text
V1      F1        C        F2      V2
●────────●────────○────────●────────●
        ←── c ─→ ←── c ─→

←────────────── 2a ──────────────→
```

Si el eje mayor es vertical,

$$
F_1=(h,k-c),
\qquad
F_2=(h,k+c).
$$

```text
          V2
          ●
          │
         F2
          ●
          │
          ○ C
          │
         F1
          ●
          │
          ●
          V1
```

## Ejemplo

Resolver

$$
x^2+4y^2-6x-16y+21=0.
$$

Completando cuadrados,

$$
\frac{(x-3)^2}{16}+
\frac{(y-2)^2}{4}=1.
$$

Centro

$$
(3,2)
$$

Semieje mayor

$$
a=4
$$

Semieje menor

$$
b=2
$$

Calculamos

$$
c=\sqrt{a^2-b^2}
=\sqrt{16-4}
=2\sqrt3.
$$

Como el eje mayor es horizontal,

$$
F_1=(3-2\sqrt3,2),
$$

$$
F_2=(3+2\sqrt3,2).
$$

## Aplicaciones

- Órbitas planetarias.
- Acústica.
- Arquitectura.
- Mecanismos elípticos.

---

# Hipérbola

## Idea central

La **hipérbola** es el conjunto de puntos cuya **diferencia de distancias a dos focos** permanece constante.

## Ecuación canónica

Horizontal

$$
\frac{(x-h)^2}{a^2}-
\frac{(y-k)^2}{b^2}=1
$$

Vertical

$$
\frac{(y-k)^2}{a^2}-
\frac{(x-h)^2}{b^2}=1.
$$

## Elementos

- Centro.
- Vértices.
- Focos.
- Asíntotas.

Los focos se calculan mediante

$$
c^2=a^2+b^2.
$$

Las asíntotas son

$$
y-k=\pm\frac ba(x-h).
$$

## Ejemplo

Resolver

$$
4x^2-3y^2+8x+12y-4=0.
$$

Completando cuadrados,

$$
\frac{(x+1)^2}{3}-
\frac{(y-2)^2}{4}=1.
$$

Centro

$$
(-1,2)
$$

Asíntotas

$$
y-2=\pm\frac{2}{\sqrt3}(x+1).
$$

## Aplicaciones

- GPS.
- Radioastronomía.
- Navegación.
- Torres de refrigeración hiperboloides.

---

# Estrategia general para resolver ejercicios

1. Ordenar la ecuación.
2. Agrupar los términos en \(x\) e \(y\).
3. Completar cuadrados.
4. Llevar la ecuación a la forma canónica.
5. Identificar la cónica.
6. Calcular todos sus elementos.
7. Realizar un bosquejo de la gráfica.

---

# Errores frecuentes

:::{warning}

- No dividir toda la ecuación por el coeficiente común.
- Completar cuadrados incorrectamente.
- Cambiar el signo del centro.
- Confundir \(r\) con \(r^2\).
- No calcular los focos.
- Olvidar las asíntotas en la hipérbola.

:::

---

# Resumen

| Cónica | Propiedad característica | Forma canónica |
|--------|---------------------------|----------------|
| Circunferencia | Distancia constante al centro | \((x-h)^2+(y-k)^2=r^2\) |
| Parábola | Distancia al foco = distancia a la directriz | \((x-h)^2=4p(y-k)\) |
| Elipse | Suma de distancias a los focos constante | \(\frac{(x-h)^2}{a^2}+\frac{(y-k)^2}{b^2}=1\) |
| Hipérbola | Diferencia de distancias a los focos constante | \(\frac{(x-h)^2}{a^2}-\frac{(y-k)^2}{b^2}=1\) |

---

# Consejos

- Identificá primero el tipo de cónica.
- Llevá siempre la ecuación a la forma canónica.
- Dibujá un bosquejo indicando los elementos principales.
- Especificá centro, vértices, focos, ejes y asíntotas cuando corresponda.
- Verificá que la ecuación final esté correctamente normalizada antes de interpretar sus parámetros.