Felipe Cruz Pineda, Angie Vargas- M6A
# Solución de ecuaciones diferenciales 
En este apartado del resumen, exploraremos varios temas clave, comenzando con la descomposición en fracciones parciales, pero utilizando un enfoque más simplificado y resumido que el método visto anteriormente. Este procedimiento nos permitirá descomponer funciones de manera eficiente, facilitando su análisis y resolución.

Además, profundizaremos en la solución de la transformada inversa y de la transformada de Laplace, empleando el programa MATLAB como herramienta principal. Veremos cómo este software nos proporciona un enfoque más práctico y sencillo para resolver ecuaciones complejas, destacando su utilidad en contextos reales.

Por último, abordaremos la solución de ecuaciones, donde analizaremos paso a paso el proceso necesario para resolver este tipo de problemas y obtener soluciones concretas. Este tema nos permitirá comprender con mayor claridad las estrategias y técnicas requeridas para enfrentar desafíos matemáticos en el ámbito de la dinámica de sistemas.


## 3. Tercer día de clase
Aprendimos a la descomposicion de fracciones parciales con los 3 casos. También se comprendio que es muy importandte el discriminante lo importante sobre las soluciones, debido a la clasificación de las soluciones de la ecuación cuadrática de la siguiente manera:

Si el discriminante, $d>0$, habrá dos soluciones distintas.
Si el discriminante, $d=0$, habrá una sola solución.
Si el discriminante, $d<0$, no hay soluciones reales, pero sí hay soluciones compleja.

🔑*Caso 1*: Raíces reales diferentes

<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=G\left(s\right)=\frac{P\left(s\right)}{(s^2 + b_1 s + c_1)(s^2 + b_2 s + c_2)}"><img src="http://www.alciro.org/cgi/tex.cgi?G\left(s\right)=\frac{P\left(s\right)}{(s^2 + b_1 s + c_1)(s^2 + b_2 s + c_2)}" title="G\left(s\right)=\frac{P\left(s\right)}{(s^2 + b_1 s + c_1)(s^2 + b_2 s + c_2)}" border="0" /></a>
</center>

🔑*Caso 2*: Raíces reales iguales

<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{P\left(s\right)}{(s-b_1)^k\left(s-b_2\right)\dots\left(s-b_n\right)}=\frac{A_1}{(s-b_1)}+\frac{A_2}{(s-b_1)^2}+\dots+\frac{A_k}{(s-b_1)^k}+\frac{A_{k+1}}{(s-b_2)}+\dots+\frac{A_n}{(s-b_n)}">
<img src="http://www.alciro.org/cgi/tex.cgi?\frac{P\left(s\right)}{(s-b_1)^k\left(s-b_2\right)\dots\left(s-b_n\right)}=\frac{A_1}{(s-b_1)}+\frac{A_2}{(s-b_1)^2}+\dots+\frac{A_k}{(s-b_1)^k}+\frac{A_{k+1}}{(s-b_2)}+\dots+\frac{A_n}{(s-b_n)}" title="\frac{P\left(s\right)}{(s-b_1)^k\left(s-b_2\right)\dots\left(s-b_n\right)}=\frac{A_1}{(s-b_1)}+\frac{A_2}{(s-b_1)^2}+\dots+\frac{A_k}{(s-b_1)^k}+\frac{A_{k+1}}{(s-b_2)}+\dots+\frac{A_n}{(s-b_n)}" border="0" />
</a>
</center>


🔑*Caso 3*: Raíces complejas conjugadas
<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{P\left(s\right)}{(s^2 + b_1 s + c_2)(s - r)}=\frac{A s + B}{(s^2 + b_1 s + c_2)}+\frac{C}{(s - r)}">
<img src="http://www.alciro.org/cgi/tex.cgi?\frac{P\left(s\right)}{(s^2 + b_1 s + c_2)(s - r)}=\frac{A s + B}{(s^2 + b_1 s + c_2)}+\frac{C}{(s - r)}" title="\frac{P\left(s\right)}{(s^2 + b_1 s + c_2)(s - r)}=\frac{A s + B}{(s^2 + b_1 s + c_2)}+\frac{C}{(s - r)}" border="0" />
</a>
</center>

📚 **Ejercicio 3:** $F=(2s-3)/(s^3+s)$
```
syms s t
F=(2*s-3)/(s^3+s)
pretty(F)
f=ilaplace(F)

```
| **Incógnita** | ** Resultado **  |
|---------------|------------------|
|       A       |        1/2       |
|       B       |      -7/2        |
|       C       |       -5/2       |

>![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_5.1_page-0001.jpg))

** Resultado ejercicio 1:  2*exp(-t) - 6*exp(-2*t) - 8*t*exp(-2*t)
📚 **Ejercicio 3:** F=(3*s+8)/(s^2+2*s+5)

>![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_5.3_page-0001.jpg))

** Resultado ejercicio 3 :** 3*exp(-t)*(cos(2*t) + (5*sin(2*t))/6)
