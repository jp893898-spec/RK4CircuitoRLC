# Actividad Tema 6.3: Sistemas de EDOs y RK4 Vectorial (Circuito RLC)

*Asignatura:* SCC-1017 Métodos Numéricos  
*Docente:* Víctor Hugo Vásquez Herrera  
*Institución:* Instituto Tecnológico Superior de Xalapa (ITSX) — Ingeniería en Sistemas Computacionales[cite: 1]

---

## Descripción

Implementación en Java del método de *Runge-Kutta de 4to orden (RK4) vectorial* para simular la respuesta libre de un circuito RLC serie con $L = 1\text{ H}$, $R = 0.4\ \Omega$ y $C = 1\text{ F}$, partiendo de su ecuación diferencial de segundo orden reducida a un sistema equivalente de primer orden[cite: 1]:

$$\begin{cases} y_1' = y_2 \\ y_2' = -y_1 - 0.4y_2 \end{cases}, \qquad \vec{Y}(0) = \begin{bmatrix} 1.0 \\ 0.0 \end{bmatrix}$$
[cite: 1]

Donde:
* $y_1(t) = q(t)$ representa la carga en el capacitor[cite: 1].
* $y_2(t) = q'(t)$ representa la corriente en el circuito[cite: 1].



