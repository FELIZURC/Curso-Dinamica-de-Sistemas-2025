## 2. Segundo dia de clase 
Recordamos y aprendimos a la descomposicion de fracciones parciales con los 3 casos.
### 2.1 Descomposicion de fracciones parciales
> 🔑*Caso 1*: Q(s) tiene raíces reales distintas.
>
<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{P\left(s\right)}{(s-p_1)\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}">
<img src="http://www.alciro.org/cgi/tex.cgi?\frac{P\left(s\right)}{(s-p_1)\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}" title="\frac{P\left(s\right)}{(s-p_1)\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}" border="0" />
</a>
</center>

>
> Entonces,
>
<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{A}{(s+p_1)}+\frac{B}{(s+p_2)}+...\frac{N}{(s+p_{n)}}"><img src="http://www.alciro.org/cgi/tex.cgi?\frac{A}{(s+p_1)}+\frac{B}{(s+p_2)}+...\frac{N}{(s+p_{n)}}" title="\frac{A}{(s+p_1)}+\frac{B}{(s+p_2)}+...\frac{N}{(s+p_{n)}}" border="0" /></a>
</center>

> 🔑*Caso 2*:Que N tiene raices reales repetidos.
<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{P\left(s\right)}{(s-p_1)^k\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_1)^2}+\dots+\frac{A_k}{(s-p_1)^k}+\frac{A_{k+1}}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}">
<img src="http://www.alciro.org/cgi/tex.cgi?\frac{P\left(s\right)}{(s-p_1)^k\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_1)^2}+\dots+\frac{A_k}{(s-p_1)^k}+\frac{A_{k+1}}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}" title="\frac{P\left(s\right)}{(s-p_1)^k\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_1)^2}+\dots+\frac{A_k}{(s-p_1)^k}+\frac{A_{k+1}}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}" border="0" />
</a>
</center>

> 🔑*Caso 3*: Q(s), tiene raices complejas conjugadas.
<center>
<a href="http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp?eq=\frac{P\left(s\right)}{(s-p_1)^k\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_1)^2}+\dots+\frac{A_k}{(s-p_1)^k}+\frac{A_{k+1}}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}">
<img src="http://www.alciro.org/cgi/tex.cgi?\frac{P\left(s\right)}{(s-p_1)^k\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_1)^2}+\dots+\frac{A_k}{(s-p_1)^k}+\frac{A_{k+1}}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}" title="\frac{P\left(s\right)}{(s-p_1)^k\left(s-p_2\right)\dots\left(s-p_n\right)}=\frac{A_1}{(s-p_1)}+\frac{A_2}{(s-p_1)^2}+\dots+\frac{A_k}{(s-p_1)^k}+\frac{A_{k+1}}{(s-p_2)}+\dots+\frac{A_n}{(s-p_n)}" border="0" />
</a>
</center>

📚 **Ejercicio 1:** $F=(3s+2)/(s(s+1)*(s-2))$

💡**Código 1:**
```
syms s t
F=(3s+2)/(s(s+1)*(s-2))
pretty(F)
f=ilaplace(F)

```
| **Incógnita** | ** Resultado **  |
|---------------|------------------|
|       A       |       -1         |
|       B       |       4/3        |
|       C       |       −1/3       |


>> >![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_1_github_page-0001.jpg))

** Resultado ejercicio 1 :** (4*exp(2*t))/3 - exp(-t)/3 - 1

📚 **Ejercicio 2:** $F=(s-2)/((2s-1)^2*(s-1))$
💡**Código 2:**
```
syms s t
F=(s-2)/((2*s-1)^2*(s-1))
pretty(F)
f=ilaplace(F)

```
| **Incógnita** | ** Resultado **  |
|---------------|------------------|
|       A       |        2         |
|       B       |        3         |
|       C       |        -1        |

>> >![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_2_page-0001.jpg))

** Resultado ejercicio 2 :**exp(t/2) - exp(t) + (3*t*exp(t/2))/4

📚 **Ejercicio 3:** $F=(2s-3)/(s^3+s)$
```
syms s t
F=(2*s-3)/(s^3+s)
pretty(F)
f=ilaplace(F)

```
| **Incógnita** | ** Resultado **  |
|---------------|------------------|
|       A       |        3         |
|       B       |        2         |
|       C       |        -3        |

>> >![](https://github.com/FELIZURC/Dinamica-de-sistemas/blob/main/Figure_3_page-0001.jpg))

** Resultado ejercicio 3 :** 3*cos(t) + 2*sin(t) - 3


| **Resultado** | **x = número de intentos hasta primer éxito** |
|---------------|-----------------------------------------------|
|       S       |                       1                       |
|       FS      |                       2                       |
|      FFS      |                       3                       |
|      ...      |                      ...                      |
|    FFFFFFS    |                       7                       |
|      ...      |                      ...                      |

Tabla 1. Tabla de ejemplo

Cada tabla debe llevar la etiqueta que describa su contenido y numeración consecutiva para todas las tablas

## 8. Código
Teniendo en cuenta que el curso requiere del desarrollo de código matlab, c, c++ u otro. Si requiere incluir pequeños segmentos de código en los apuntes hágalos de la siguiente manera:

💡**Ejemplo 4:**
```
var sumar2 = function(numero) {
  return numero + 2;
}
```

## 9. Ejercicios
Deben agregar 2 ejercicios con su respectiva solución, referentes a los temas tratados en cada una de las clases. Para agregar estos, utilice la etiqueta #, es decir como un nuevo título dentro de la clase con la palabra 'Ejercicios'. Cada uno de los ejercicios debe estar numerado y con su respectiva solución inmediatamente despues del enunciado. Antes del subtitulo de cada ejercicio incluya el emoji 📚

## Rúbrica
| 0-1                                                                                   | 1-2                                                                                  | 2-3                                                                                                                                                                               | 3-4                                                                                                                                                                       | 4-5                                                                                                                                                                               |
|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Presenta menos del 10% de los temas o no presenta por  el medio y formato  solicitado | Presenta menos del 40% de los temas solicitados, y  cumple parcialmente la plantilla | Presenta menos del 60% de los temas solicitados (con descripciones, gráficos tablas, etc), y cumple  parcialmente la plantilla. No presenta la totalidad  de ejercicios resueltos | Presenta menos del 80% de los temas solicitados (con descripciones, gráficos, tablas, etc) y cumple con  la plantilla. No presenta  la totalidad de ejercicios  resueltos | Presenta el 100% de los temas vistos en clase (con descripciones, gráficos, tablas, etc), siguiendo totalmente la plantilla. presenta la  totalidad de los ejercicios solicitados |

## 10. Conclusiones
Agregue unas breves conclusiones sobre los temas trabajados en cada clase, puede ser a modo de resumen de lo trabajado o a indicando lo aprendido en cada clase

## 11. Referencias
Agregue un subtítulo al final donde pueda poner todas las referencias consultadas incluyendo el origen o fuente de los ejercicios planteados. Tambien dentro del texto referencie los textos o artículos consultados y las figuras y tablas dentro de la explicación de las mismas.
