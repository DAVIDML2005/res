# Problema

Asuma que la población de venados de Sincelejo es 200 en el momento \(n=0\) y 220 en el momento \(n=1\). Además, el aumento de la población del momento \(n-1\) al momento \(n\) es dos veces el aumento del momento \(n-2\) al momento \(n-1\).

Determine:
1. La ecuación de recurrencia que modela la población de venados.
2. La ecuación no recurrente (fórmula cerrada).

## Inicio de la solución

Partimos de la condición del problema:

$$
f_n-f_{n-1}=2\left(f_{n-1}-f_{n-2}\right)
$$

Desarrollando la expresión:

$$
\begin{aligned}
f_n-f_{n-1} &= 2f_{n-1}-2f_{n-2} \\
f_n &= 3f_{n-1}-2f_{n-2}
\end{aligned}
$$

La relación de recurrencia obtenida es:

$$
\boxed{f_n=3f_{n-1}-2f_{n-2}}
$$

---

# Desafío para la comunidad

¿Puedes resolver la siguiente relación de recurrencia?

$$
f_n=4f_{n-1}-4f_{n-2}
$$

con condiciones iniciales

$$
f_0=1,\qquad f_1=3.
$$

> **Pista:** El polinomio característico tiene una raíz doble.
