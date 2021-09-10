---
title: Economía II
author: Héctor G. T. Torres
header-includes:
- \ifdefined\HCode\def\pgfsysdriver{pgfsys-dvisvgm4ht.def}\fi
- \usepackage{tikz}
- \usepackage{pgfplots}
---

\maketitle
\thispagestyle{empty}
\clearpage
\tableofcontents
\pagenumbering{roman}
\clearpage
\pagenumbering{arabic}
\setcounter{page}{1}

# Variables para todo el curso

|Variable|Significado|
|--------|-----------|
|$_0$ (Subíndice $0$)|Variable en año base o Variable autónoma|
|$_1$(Subíndice $1$)|Variable en año corriente o Variable sensible|
|$_2$(Subíndice $2$)|Variable aún más sensible|
|$Y$|Ingresos/PIB/Producción|
|$Y^D$|Ingreso Disponible|
|$Z$|Demanda|
|$C$|Consumo|
|$I$|Inversión|
|$G$|Gasto|
|$Tg$|Transferencias|
|$XN$|Balanza comercial|
|$\pi$|Inflación|
|$L$|Población Económicamente Activa|
|$N$|Empleados|
|$U$|Desempleados|
|$VA$|Valor agregado|
|$PB$| Producción bruta|
|$CI$|Consumo Intermedio|
|$RA$|Renumeración a asalariados|
|$EE$|Excedente de Explotación|
|$D$|Depreciación|
|$II$|Impuestos indirectos|
|$S$|Subsidios/Ahorros|
|$X$|Exportaciones|
|$IM$|Importaciones|
|$BP$|Balanza de pagos|
|$CC$|Cuenta Corriente|
|$CK$|Cuenta Capital|
|$EyO$|Errores y Omisiones|
|$\text{INIE}$|Ingresos Netos por Inversiones en el Extranjero|
|$\text{TNE}$|Transferencias Netas con el Extranjero|
|$AE$|Ahorro Externo|
|$c_1$|Propensión Marginal a Consumir|
|$T_0$|Impuestos Autónomos|
|$t_1$|Tasa impositiva|
|$b_1$|Sensibilidad de la inversión ante cambios en el ingreso|
|$b_2$|Sensibilidad de la inversión ante cambios en la tasa de interés|
|$CU$|Efectivo|
|$R$|Reservas|
|$H$|High Power Money/Base Monetaria/Oferta del Banco Central|
|$H^d$|Demanda de efectivo|
|$M^d$|Demanda de Dinero total|
|$\theta$|Demanda de Dinero total|

\clearpage

# Primer Parcial

## Definiciónes

### Microeconomía
Estudia el comportamiento de individuos, familiar, empresas y mercados de manera **individual**.

### Macroeconomía (este curso)
Estudia el comportamiendo como un agregado de todos los actores económicos (todos los individuos, todas las familias, todas las empresas, etc). Por lo tanto, tiene una visión **global**.  

En el curso, se analizarán 3 variables principales:

+ **PIB**
+ **Inflación**
+ **Desempleo**

### Plazos en la economía

#### Corto plazo - Primer parcial
Aquél en el que las empresas/agentes económicos cuya producción depende de *factores de la producción* (es decir, capital [maquinaria, tecnología, tierras, etc.] y trabajo), **no los pueden cambiar**. Por lo tanto, **los precios no cambian**.

#### Mediano plazo - Segundo parcial
Las empresas/agentes económicos pueden modificar el **factor trabajo** (es decir, pueden contratar y despedir gente(. Por lo tanto, **los precios cambian**.

#### Largo plazo - Tercer parcial
Las empresas/agentes económicos pueden modificar el **factor trabajo y el factor capital** (pueden contratar, despedir, y comprar maquinaria y otros activos). Por lo tanto, **los precios cambian**.

### PIB
El **valor total** de todos los **bienes y servicios finales producidos** en una economía en un **periodo determinado**. Es **lo mismo** que la **producción total** y los **ingresos totales** de la economía.  

No incluye bienes y servicios importados, ilegales, de consumo intermedio, o usados.

### Inflación
Es el **aumento sostenido**(por al menos 2 trimestres) de **precios** generalizados para una canasta de bienes y servicios. Se expresa en porcentaje.

#### Fórmula

$$
\begin{gathered}
\pi = (\frac{\text{Valor}_{final}}{\text{Valor}_{inicial}}-1)100 
\end{gathered}
$$

### Desempleo
Es el **número de personas desempleadas**. Para que una persona sea considerada **desempleada** debe:

+ Querer y poder trabajar
+ Estar buscando activamente un trabajo
+ Ser mayor a 15 años de edad (**Edad activa**)
+ No tener trabajo

#### PEA (Población Económicamente Activa)
La población que quiere y puede trabajar, y está en edad activa. **Se divide en Empleados y Desempleados**.

#### PNEA (Población No Económicamente Activa)
La población que no quiere y/o no puede trabajar y está en edad activa.

#### Fórmulas

$$
\begin{gathered}
\text{Tasa de desempleo} = U = \frac{U}{L}100\\
\text{Tasa de actividad} = \frac{L}{\text{Número de personas en Edad activa}}100\\
\text{Tasa de empleo} = \frac{N}{L}100
\end{gathered}
$$

## Medición del PIB

### Por el lado de la Producción

$$
\begin{gathered}
\text{PIB} = \sum VA = PB-CI =\sum\text{ventas} - \sum\text{insumos}
\end{gathered}
$$

### Por el lado del Ingreso/a Precios de mercado/Costos de facctores

$$
\begin{gathered}
\text{PIB}_{pm} = RA+EE+D+II-S \\
\text{PIB}_{cf} = RA+EE+D\\
\therefore \text{PIB}_{pm}=\text{PIB}_{cf}+II-S
\end{gathered}
$$

### Por el lado de la Demanda

$$
\begin{gathered}
\text{PIB} = C+I+G+XN
\end{gathered}
$$

### Producto Interno Neto

$$
\begin{gathered}
\text{PIN}_{pm}=RA+EE+II-S=\text{PIB}_{pm}-D
\end{gathered}
$$

### Producto Nacional Bruto
Todos los bienes y servicios producidos por los ciudadanos/empresas/agentes económicos de una nación (ej. el PIB incluye lo que produjo Bimbo en México, pero no en China. El PNB incluye ambos).

### PIB nominal, real y potencial

#### PIB nominal
La producción de un periodo representaba con los precios de ese periodo.

#### PIB Real
La producción de un periodo representaba con los precios de un año base.

#### PIB Potencial/eficiente/natural
El PIB de una economía si utilizara todos sus recursos eficientemente y hubiera el menor desempleo posible.

## Ciclos económicos

+ **Expansión** La economía **crece** a tasas **crecientes**
+ **Contracción** La economía **crece** a tasas **decrecientes**
+ **Recesión** La economía **decrece** a tasas **decrecientes**
+ **Recuperación** La economía **decrece** a tasas **crecientes**

## Balanza de pagos
Registro de todas las transacciones monetarias que hace un país con el resto del mundo. **Siempre tiene que valer 0**.

$$
\begin{gathered}
BP=CC+CK+EyO
\end{gathered}
$$

### Cuenta Corriente ($CC$)
Se **suman los pagos que entran** al país y se **restan los pagos que salen**.
$$
\begin{gathered}
CC= \text{INIE} + \text{TNE} + XN
\end{gathered}
$$

#### Ingresos Netos por Inversiones con el Extranjero ($\text{INIE}$)
Es una balanza de servicios. Por lo cuál, entran todas las ganancias de las empresas (utilidades) y pagos de las inversiones.

#### Transferencias Netas con el Extranjero ($\text{TNE}$)
Es una balanza de transferencias. Aquí van las remesas y donaciones.

#### Balanza comercial ($XN$)
Exportaciones menos importaciones.

$$
\begin{gathered}
XN = X-IM
\end{gathered}
$$

### Cuenta Capital ($CK$)
La compra y venta de activos, ya sea reales (tangibles) o financieros (intangibles) Se **suman los activos que los foráneos tengan en mi país** y se **restan los activos que los nacionales tengan en el extranjero**.

### Ahorro Externo ($AE$)
Es lo que el resto del mundo ahorra o pide prestado a un país.

$$
\begin{gathered}
AE = -CC
\end{gathered}
$$

#### Ahorro Externo Positivo
Significa que

+ El país pide dinero prestado
+ El resto del mundo le presta al país
+ El país debe dinero/es deudor

#### Ahorro Externo Negativo
Significa que

+ El país presta dinero
+ El resto del mundo le pide prestado al país
+ El país es acreedor a deuda

##### Nota
A veces, el departamento pone que

$$
\begin{gathered}
AE = -XN
\end{gathered}
$$
Por lo tanto,

$$
\begin{gathered}
\text{INIE} = \text{TNE} =0
\end{gathered}
$$

## Índices de Precios
Promedios ponderados (según las cantidades) de los precios de una canasta de bienes y servicios. En el año base valen 100.

### Índice de Paasche

$$
\begin{gathered}
\mathbb P = \sum \frac{\sum Q_1 P_1}{\sum Q_1 P_0}100
\end{gathered}
$$

#### Deflactor del PIB 
El deflactor es un índice $\mathbb P$ que usa como canasta los bienes y servicios del PIB.

$$
\begin{gathered}
D = \mathbb P = \frac {\text{PIB nominal}}{\text{PIB real}}100
\end{gathered}
$$

### Índice de Laspeyres

$$
\begin{gathered}
\mathbb L = \sum \frac{\sum Q_0 P_1}{\sum Q_0 P_0}100
\end{gathered}
$$

#### Índice Nacional de Precios al Consumidor ($\text{INPC}$)
Es un índice $\mathbb L$ que usa como canasta los bienes de consumo

\clearpage

# Segundo Parcial

## Mercado de Bienes y Servicios

#### Supuestos

+ Todas las personas son racionales y se comportan igual
+ Estamos en corto plazo
	\begin{tikzpicture}
		\begin{axis}
			[
			xmin=0, xmax=10,
			ymin=0, ymax=10,
			axis lines* = left,
			xtick = {0}, ytick = \empty,
			clip = false,
			very thick
			]
			\addplot[color = black, very thick] coordinates {(0,5)(9,5)};
			\addplot[color = black, very thick] coordinates {(1,9)(9,1)};
			\node [right] at (current axis.right of origin) {$Q$};
			\node [above] at (current axis.above origin) {$P$};
			\node [right] at (90,50) {Oferta Agregada};
			\node [right] at (90,10) {Demanda Agregada};
		\end{axis}
	\end{tikzpicture}
	- No cambia la Oferta Agregada
	- Solo cambia la Demanda Agregada
		+ **Solo** se modifican los precios ($P$), **no** la cantidad $(Q)$
+ La Economía es una Economía Cerrada
	- $IM = 0, X = 0 \implies XN=0$
	- $AE = 0, CC = 0, CK=0$
	- No hay inventarios en equilibrio
		+ $\implies$ Producción/$\text{PIB} (Y) =$ Demanda$(Z)$
	\begin{tikzpicture}
		\begin{axis}
			[
			xmin=0, xmax=10,
			ymin=0, ymax=10,
			axis lines* = left,
			xtick = {0}, ytick = \empty,
			clip = false,
			very thick
			]
			\addplot[color = black, very thick] coordinates {(0,0)(9,9)};
			\node [right] at (current axis.right of origin) {$Y$};
			\node [above] at (current axis.above origin) {$Z$};
			\node [right] at (90,90) {$Y=Z$};
			\node [right] at (100,100) {El equilibrio estará sobre esta recta};
		\end{axis}
	\end{tikzpicture}
	\begin{tikzpicture}
		\begin{axis}
			[
			xmin=0, xmax=10,
			ymin=0, ymax=10,
			axis lines* = left,
			xtick = {0}, ytick = \empty,
			clip = false,
			very thick
			]
			\addplot[color = black, very thick] coordinates {(0,0)(9,9)};
			\addplot[color = black, very thick] coordinates {(0,3)(9,6)};
			\addplot[color = black, mark = *] coordinates {(4.5,4.5)};
			\addplot[color = black, dashed, thick] coordinates {(4.5,0)(4.5,4.5)};
			\node [right] at (current axis.right of origin) {$Y$};
			\node [above] at (current axis.above origin) {$Z$};
			\node [right] at (90,90) {$Y=Z$ "Oferta"};
			\node [right] at (90,60) {$Z$ Demanda};
			\node [below] at (45,0) {$Y_{eq}$};
		\end{axis}
	\end{tikzpicture}
+ A la izquierda del equilibrio hay un **Exceso de Demanda**
	- Para resolverlo, las empresas deben **liberar inventarios**
+ A la derecha del equilibrio hay un **Exceso de Oferta**
	- Para resolverlo, las empresas deben **acumular inventarios**

### Encontrando el $\text{PIB}$ de Equilibrio $(Y_{eq})$

#### Primera forma: $Y = C + I + G$

+ La fórmula del **PIB** es
$$
\begin{gathered}
Y = C + I + G
\end {gathered}
$$
	- La fórmula de **Consumo $(C)$** es
$$
\begin{gathered}
C = C_0 + c_1 Y^D \\
C = f(Y,T,Tg) \text{ de manera } +,-,+
\end {gathered}
$$
		+ $C_0$ Consumo autónomo
		+ $c_1$ Propensión marginal a consumir
		+ $Y^D$ Ingreso Disponible
			- $Y^D = C + S (\text {Ahorro})$
			- $Y^D = Y - T + Tg$
		+ $T = T_0 + t_1 Y$
			- $T_0$ Impuestos autónomos
			- $t_1$ Tasa impositiva
	- Las fórmulas de **Inversión $(I)$** son
$$
\begin{gathered}
I = b_0 + b_1 Y - b_2 i \\
I = S_p + S_{gov} + AE \\
I = f(Y,i) \text{ de manera } +,-
\end {gathered}
$$

		- $b_0$ Inversión autónoma
		- $b_1$ Sensibilidad de la inversión ante cambios del ingreso
		- $b_2$ Sensibilidad de la inversión ante cambios en la tasa de interés
		- $S_p$ Ahorro privado
			+ $S_{gov} = T_0 + t_1Y - G - Tg$
		- $S_gov$ Ahorro del gobierno
			+ $S_p = S = C_0 + (1-c_1)Y^D$
			+ $S_p = Y^D -  C$
		- $AE = -CC$

#### Segunda Forma
+ La fórmula del **PIB** es
$$
\begin{gathered}
Y = \alpha [A_0 - b_2 i]
\end{gathered}
$$

	- $\alpha$ Multiplicador Keynesiano
$$
\begin{gathered}
\alpha = \frac{1}{1 - [c_1(1-t_1)+b_1]} \\
\alpha = f(c_1,t_1,b_1) \text{ de manera } +,-,+
\end{gathered}
$$

		+ $m_Z$ Pendiente de $Z$
			- $m_Z = 1 - [c_1(1-t_1)+b_1]$
	- $A_0$ Ahorro autónomo
$$
\begin{gathered}
A_0 = C_0 - c_1T_0+b_0+G+c_1Tg
\end{gathered}
$$
\begin{center}
	\begin{tikzpicture}
		\begin{axis}
			[
			xmin=0, xmax=10,
			ymin=0, ymax=10,
			axis lines* = left,
			xtick = {0}, ytick = \empty,
			clip = false,
			very thick
			]
			\addplot[color = black, very thick] coordinates {(0,0)(9,9)};
			\addplot[color = black, very thick] coordinates {(0,3)(9,6)};
			\addplot[color = black, mark = *] coordinates {(4.5,4.5)};
			\addplot[color = black, dashed, thick] coordinates {(4.5,4.5)(6,4.5)(6,5)};
			\addplot[color = black, dashed, thick] coordinates {(4.5,4.5)(4.5,0)};
			
			\node [right] at (current axis.right of origin) {$Y$};
			\node [right] at (60,45) {$m_Z = 1-[c_1(1-t_1)+b_1]$};
			\node [above] at (current axis.above origin) {$Z$};
			\node [right] at (90,90) {$Y=Z = C + I + G$ };
			\node [right] at (90,60) {$Z = C + I + G$ };
			\node [below] at (45,0) {$Y_{eq}$};
			\node [left] at (0,30) {$A_0 - b_2 i$};
		\end{axis}
	\end{tikzpicture}
\end{center}
### Movimientos de $Z$

#### Desplazamientos
Al desplazarse la curva de $Z$...
\begin{center}
	\begin{tikzpicture}
		\begin{axis}
			[
			xmin=0, xmax=10,
			ymin=0, ymax=10,
			axis lines* = left,
			xtick = {0}, ytick = \empty,
			clip = false,
			very thick
			]
			\addplot[color = black, very thick] coordinates {(0,0)(9,9)};
			\addplot[color = black, very thick] coordinates {(0,3)(9,6)};
			\addplot[color = black, dashed, very thick] coordinates {(0,5)(9,8)};
			\addplot[color = black, dashed, very thick] coordinates {(0,1)(9,4)};
			\addplot[color = black, dashed, mark = *] coordinates {(4.5,0)(4.5,4.5)};
			
			\node [right] at (current axis.right of origin) {$Y$};
			\node [above] at (current axis.above origin) {$Z$};
			\node [right] at (90,90) {$Y=Z$ };
			\node [right] at (90,60) {$Z = C + I + G$ };
			\node [right] at (90,80) {$\uparrow C_0, \downarrow T_0, \uparrow G, \uparrow Tg$ };
			\node [right] at (90,40) {$\downarrow C_0, \uparrow T_0, \downarrow G, \downarrow Tg$ };
			\node [below] at (45,0) {$Y_{eq}$};
			\node [left] at (0,30) {$A_0 - b_2 i$};
		\end{axis}
	\end{tikzpicture}
\end{center}
#### Cambio de Pendiente $m_Z$
Al cambiar la pendiente de $Z$...
\begin{center}
	\begin{tikzpicture}
		\begin{axis}
			[
			xmin=0, xmax=10,
			ymin=0, ymax=10,
			axis lines* = left,
			xtick = {0}, ytick = \empty,
			clip = false,
			very thick
			]
			\addplot[color = black, very thick] coordinates {(0,0)(9,9)};
			\addplot[color = black, very thick] coordinates {(0,3)(9,6)};
			\addplot[color = black, dashed, very thick] coordinates {(0,3)(9,8)};
			\addplot[color = black, dashed, very thick] coordinates {(0,3)(9,4)};
			\addplot[color = black, dashed, mark = *] coordinates {(4.5,0)(4.5,4.5)};
			
			\node [right] at (current axis.right of origin) {$Y$};
			\node [above] at (current axis.above origin) {$Z$};
			\node [right] at (90,90) {$Y=Z$ };
			\node [right] at (90,60) {$Z = C + I + G$ };
			\node [right] at (90,80) {$\uparrow c_1, \downarrow t_1, \uparrow b_1$ };
			\node [right] at (90,40) {$\downarrow c_1, \uparrow t_1, \downarrow b_1$ };
			\node [below] at (45,0) {$Y_{eq}$};
			\node [left] at (0,30) {$A_0 - b_2 i$};
		\end{axis}
	\end{tikzpicture}
\end{center}
##### Políticas Fiscales
Herramientas del gobierno para influir en la economía cambiando $T$ o $G$.
\begin{center}
	\begin{tikzpicture}
		\begin{axis}
			[
			xmin=0, xmax=10,
			ymin=0, ymax=10,
			axis lines* = left,
			xtick = {0}, ytick = \empty,
			clip = false,
			very thick
			]
			\addplot[color = black, very thick] coordinates {(0,0)(9,9)};
			\addplot[color = black, very thick] coordinates {(0,3)(9,6)};
			\addplot[color = black, dashed, very thick] coordinates {(0,5)(9,8)};
			\addplot[color = black, dashed, very thick] coordinates {(0,1)(9,4)};
			\addplot[color = black, dashed, mark = *] coordinates {(4.5,0)(4.5,4.5)};
			\addplot[color = black, dashed, mark = *] coordinates {(7.5,0)(7.5,7.5)};
			\addplot[color = black, dashed, mark = *] coordinates {(1.5,0)(1.5,1.5)};
			
			\node [right] at (current axis.right of origin) {$Y$};
			\node [above] at (current axis.above origin) {$Z$};
			\node [right] at (90,90) {$Y=Z$ };
			\node [right] at (90,60) {$Z = C + I + G$ };
			\node [right] at (90,80) {$\downarrow T_0, \uparrow G$ };
			\node [right] at (90,40) {$\uparrow T_0, \downarrow G$ };
			\node [below] at (45,0) {$Y_{eq}^0$};
			\node [below] at (74,0) {$Y_{eq}^1$};
			\node [below] at (15,0) {$Y_{eq}^2$};
			\node [left] at (0,30) {$A_0 - b_2 i$};
		\end{axis}
	\end{tikzpicture}
\end{center}
+ Sólo pueden cambiar $G$ y $T$ (si cambian $Tg$ son políticas sociales
+ **P. Fiscal Expansiva:** $\uparrow G, \downarrow T$
+ **P. Fiscal Contractiva:** $\downarrow G, \uparrow T$

#### Fórmulas de Cambios

+ Sirven para ver como cambia el **PIB** ante el cambio de alguna otra variable
+ Suponemos que $b_2 i$ no cambia ($\Delta b_2 i = 0$)
+ Tomamos en cuenta la fórmula $Y =  \alpha [A_0 - b_2 i]$

	- $\Delta Y = \alpha \Delta A_0$
	- $\Delta Y = \alpha \Delta C_0$
	- $\Delta Y = \alpha \Delta I_0 = \alpha \Delta b_0$
	- $\Delta Y = -c_1 \alpha \Delta T_0$
	- $\Delta Y = \alpha c_1 \Delta Tg$
	- $\Delta Y = \alpha c_1 \Delta G$

### Paradoja del Ahorro

+ Ocurre cuando
	- $Tg =0$
	- $T = T_0 \implies t_1Y^D =0 \implies t_1=0$
	- $I = b_0 \implies b_1 Y + b_2 i =0 \implies b_1 = b_2 = 0$
	- La economía debe de ser cerrada ($I = S_p+S_{gov} \implies AE = CC = 0$)
+ Definición
Es cuando hay un cambio en el consumo ($\Delta c_0, \Delta c_1$) con la intención de aumentar el ahorro, pero, al también cambiar el consumo, cambia el ingreso de las empresas, por lo que cambia lo que producen, lo cuál afecta el ingreso de las personas.  
**Por lo tanto, el ahorro no cambia.**

\clearpage

## El Mercado Financiero

### Introducción y Supuestos

#### Definición

Mercado en el cuál hay dos agentes: los que **ahorran** su dinero (el banco) y lo prestan, y los que **deben** dinero y pagan el precio de la **tasa de interés**.  

Por lo tanto, **el objetico es encontrar la tasa de interés de equilibrio $i_{eq}$.**

#### La tasa de interés ($i$)

+ Lo que te pagan por su dinero en el banco o por un instrumento financiero (bonos)
+ Lo que de cuesta un préstamo
+ El precio del dinero

#### Supuestos
+ Economía cerrada ($X = IM = 0$)
+ Corto plazo (precios constantes)
	- Hablamos en términos nominales (monedas)
+ No hay inventarios en equilibrio

#### 3 Mercados Financieros
+ Mercado del Banco Central (trata de dinero impreso)
+ Mercado Financiero Total (trata de dinero impreso y virtual)
+ Mercado de Bonos

### Mercado Financiero del Banco Central

#### La Oferta (Base Monetaria)
+ Representada por $H$ y es un número fijo dado por el Banco Central.

#### La Demanda
+ Dada por la fórmula
$$
\begin{gathered}
H^d = CU + R
\end{gathered}
$$

	- $CU$ Efectivo (Currency)
$$
\begin{gathered}
CU = cM^d\\
c \in [0,1]
\end{gathered}
$$
		+ $c$ Porción de cuanto quieren tener las personas en efectivo
		+ $M^d$ Demanda total de dinero
	- $R$ Reservas  
	Todo lo que los bancos comerciales están obligados a mantener en efectivo.
$$
\begin{gathered}
R = \theta D = \theta (1-c) M^d \\
\theta \in [0,1]
\end{gathered}
$$
		+ $\theta$ Coeficiente de reservas
		+ $D$ Depósitos  
		Todo el dinero que las personas depositan en los bancos.
### Mercado Financiero Total

+ Incluye el dinero impreso más **dinero virtual** (el cuál es creado por varios procesos).
+ Regla general: Mientras más alta la tasa de interés, **menos efectivo demanda la gente. Prefiere invertirlo**. Mientras menos la tasa, **más efectivo demanda la gente. Prefiere consumir**.

#### Oferta Monetaria Total ($M^o$)
+ La $M^o$ es, ya sea dada, o la tienes que calcular con la fórmula
$$
\begin{gathered}
M^o = \alpha^B H
\end{gathered}
$$
	- $\alpha^B$ El Multiplicador Bancario
$$
\begin{gathered}
\alpha^B = \frac{1}{c + \theta(1-c)} \\
\alpha^B = f(c,\theta) \text{ de manera } -,-
\end{gathered}
$$

##### Desplazamientos $M^d$ (Políticas monetarias)
Los Desplazamientos en la gráfica relacionada se verían así...
\begin{center}
	\begin{tikzpicture}
		\begin{axis}
			[
			xmin=0, xmax=10,
			ymin=0, ymax=10,
			axis lines* = left,
			xtick = {0}, ytick = \empty,
			clip = false,
			very thick
			]
			\addplot[color = black, very thick] coordinates {(5,0)(5,10)};
			\addplot[color = black, dashed, very thick] coordinates {(2,0)(2,10)};
			\addplot[color = black, dashed, very thick] coordinates {(8,0)(8,10)};
			\draw[->] (52,80) to (77,80);
			\draw[->] (48,80) to (23,80);
			
			\node [right] at (current axis.right of origin) {$M$};
			\node [above] at (current axis.above origin) {$i$};
			\node [below] at (50,0) {$M_0^o$};
			\node [below] at (80,0) {$M_1^o$};
			\node [below] at (20,0) {$M_2^o$};
		\end{axis}
	\end{tikzpicture}
\end{center}
+ $M_0^o$ refleja la oferta inicial
+ $M_1^o$ refleja una **Política Fiscal Expansiva**
	- Que el B. C. **compre** bonos
	- Que **disminuya** el coeficiente de reservas
	- Que **disminuya** la propensión a tener efectivo
+ $M_2^o$ refleja una **Política Fiscal Restrictiva**
	- Que el B. C. **venda** bonos
	- Que **aumente** el coeficiente de reservas
	- Que **aumente** la propensión a tener efectivo

#### Demanda Monetaria Total ($M^d$)
+ Todo el dinero que demanda una economía

##### Fórmulas
+ $M^d = CU + D$
+ $M^d = \$ Y (\text {PIB Nominal}) + L(i) \text{ de manera } -$
	- $L(i)$ Función de Liquidez
+ $M^d = f_0 + f_1 \$ Y - f_2 i$
	- $f_0$ autónomo
	- $f_1$ dependiente de los ingresos
	- $f_2$ dependiente de la tasa de interés

##### Desplazamientos de $M^d$  
Los desplazamientos de $M^d$ se verían así
\begin{center}
	\begin{tikzpicture}
		\begin{axis}
			[
			xmin=0, xmax=10,
			ymin=0, ymax=10,
			axis lines* = left,
			xtick = {0}, ytick = \empty,
			clip = false,
			very thick
			]
			\addplot[domain = 0:10, color = black, very thick, restrict y to domain = 0:10, samples = 400] {10/(x)};
			\addplot[dashed,domain = 0:10, color = black, very thick, restrict y to domain = 0:10, samples = 400] {10/(x-3)+3};
			\draw[->] (35,35) to (60,60);
			
			\node [right] at (current axis.right of origin) {$M$};
			\node [above] at (current axis.above origin) {$i$};
			\node [right] at (100,60) {$\uparrow Y, \uparrow Y, \uparrow f_0 $};
			\node [right] at (100,10) {$M^d$};
		\end{axis}
	\end{tikzpicture}
\end{center}

\clearpage

#### El Equilibrio
Así se vería el equilibrio
\begin{center}
	\begin{tikzpicture}
		\begin{axis}
			[
			xmin=0, xmax=10,
			ymin=0, ymax=10,
			axis lines* = left,
			xtick = {0}, ytick = \empty,
			clip = false,
			very thick
			]
			\addplot[domain = 0:10, color = black, very thick, restrict y to domain = 0:10, samples = 400] {10/(x)+2};
			\addplot[color = black, very thick] coordinates {(5,0)(5,10)};
			\addplot[color = black, dashed, mark = *, very thick] coordinates {(0,4)(5,4)};
			
			\node [right] at (current axis.right of origin) {$M$};
			\node [above] at (current axis.above origin) {$i$};
			\node [right] at (100,30) {$M^d$};
			\node [below] at (50,0) {$M^o$};
			\node [left] at (0,40) {$i_{eq}$};
		\end{axis}
	\end{tikzpicture}
\end{center}

+ Arriba del equilibrio hay un **Exceso de oferta**
+ Abajo del equilibrio hay un **Exceso de demanda**

\clearpage

### Mercado de Bonos
+ Un Bono es un instrumento financiero de deuda emitido por un país. Cuando compras un bono, le estás prestando dinero a un país. **Cuando compras un bono, le estás prestando dinero a un país**. Es una alternativa a tener el dinero en efectivo ya que la inversión representa un **riesgo casi nulo** (es muy raro que un país deje de pagar su deuda; la última vez que pasó con México fue con Benito Juárez).

#### Rendimiento del bono = tasa de interés ($i$)

+ El rendimiento es el cambio porcentual ($\Delta \%$) entre el Precio del Bono/Valor Inicial ($P_B/Vi$) y el Valor Final/Valor Nominal ($VF/V_n$) del Bono.  
En una ecuación, esto es...
$$
\begin{gathered}
\Delta \% = (\frac{VF}{Vi}-1)100 \\
\implies i = (\frac{VF}{Vi}-1)100 \\
\implies i = (\frac{V_n}{P_B}-1)100 \\
\implies i = f(P_b) \text{ de manera } - \\ 
\implies P_b = f(i) \text{ de manera } - \\ 
\implies \uparrow P_b \implies \downarrow i  
\end{gathered}
$$

##### Ecuación de la Riqueza

+ Para calcular la riqueza, sigue esta ecuación
$$
\begin{gathered}
Riqueza = M^d + B^d
\end{gathered}
$$
