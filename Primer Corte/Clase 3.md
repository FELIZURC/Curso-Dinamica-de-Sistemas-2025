# Tercer día de clase
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









💡**Ejemplo 2:**

![Figura de prueba](images/plantilla/Captura2.PNG)

Figura 1. Figura de prueba

Incluya la respectiva etiqueta a modo de descripción de la figura y mantenga numeración consecutiva para todas las figuras de la clase.

## 7. Tablas
En caso de necesitar la inclusión de tablas para organizar información se recomienda el uso de la herramienta del siguiente enlace https://www.tablesgenerator.com/markdown_tables , la cual permite organizar la información dentro de la tabla y genera el código markdown automáticamente:

💡**Ejemplo 3:** 

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
