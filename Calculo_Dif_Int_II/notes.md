---
title: Apuntes Cálculo Dif. e Int. II
author: Héctor G. T. Torres
---

\maketitle
\thispagestyle{empty}
\clearpage
\tableofcontents
\pagenumbering{roman}
\clearpage
\pagenumbering{arabic}
\setcounter{page}{1}

# Recordar

## **Def** de Función acotada

Una función $f: A \to \mathbb R$ es una **función acotada** si
$$
\begin{gathered}
\exists  M \in \mathbb R^+ \land N < 0 \in \mathbb R\\
\land N<f(x)<M \forall x \in A
\end{gathered}
$$

# Notación de Sumas (Notación Sigma)

## **Def** Notación Sigma
La suma de $n$ términos $a_1,a_2,...,a_n$ se escribe
$$
\begin{gathered}
\sum_{i=1}^n a_i = a_1 + a_2 + a_3 + ... + a_n
\end{gathered}
$$
donde $i$ es el índice de la suma, $a_i$ es el $i$-ésimo término,
el límite inferior de la suma es $1$ y el límite superior es $n$.

## **Teo** Propiedades de la suma
1. $\sum_{i=1}^n c = nc$
2. $\sum_{i=1}^n (a_i+b_i) = \sum_{i=1}^n{a_i} + \sum_{i=1}^n{b_i}$
3. $\sum_{i=1}^n ca_i = c \sum_{i=1}^n a_i$

## **Teo** Fórmulas importantes
1. $\sum_{i=1}^n c = nc$
2. $\sum_{i=1}^n i = \frac {n(n+1)}{2}$
3. $\sum_{i=1}^n i^2 = \frac {n(n+1)(2n+1)}{6}$
4. $\sum_{i=1}^n i^3 = \frac {n²(n+1)^2}{4}$

# Integrales

## **Def** de Partición
Sea $[a,b]$ un intervalo. Una **partición** de $[a,b]$ es un conjunto de puntos $P = {t_0 = a, t_1, t_2,..., t_n=b}$ donde
$t_0=a<t_1<t_2<t_3<...<t_n=b$

## **Def** Suma por arriba y abajo
Sea $f$ una función acotada sobre $[a,b]$. Definimos la **Suma por arriba** de $f$ con respecto a $P$ como
$$
\begin{gathered}
\overline{S}(f,P) = \sum_{i=1}^n M_i(t_i-t_{i-1})
\end{gathered}
$$

y la **Suma por debajo** como

$$
\begin{gathered}
\underline{S}(f,P) = \sum_{i=1}^n = \sum_{i=1}^n m_i(t_i - t_{i-1})
\end{gathered}
$$

donde
$$
\begin{gathered}
M_i = \text{sup} \{ f(x)|x\in [t_{i-1},t_i]\}\\
m_i = \text{inf} \{f(x) |x \in [t_{i-1},t_i]\}
\end{gathered}
$$

## **Teo**
Sea $P$ una partición de $[a,b]$ y $Q$ una partición de $[a,b]$ con más puntos que $P$.
$$
\begin{gathered}
\implies \underline{S}(f,P)\le \underline{S}(f,Q) \le
\overline{S}(f,Q) \le \overline{S}(f,P)
\end{gathered}
$$

## **Def** Función integrable
Se dice que una función $f$ es **integrable** sobre $[a,b]$ si

$$
\begin{gathered}
\text{inf}\{\overline{S}(f,P)\} = \text{sup}\{\underline{S}(f,P)\}
\end{gathered}
$$
donde $P$ es una partición de $[a,b]$.

En este caso, a dicho número en común se le denota como
$$
\begin{gathered}
\int_{a}^{b} f(x)dx
\end{gathered}
$$

## **Teo** Continuidad
Si $f$ es contínua en $[a,b] \implies f$ es integrable en $[a,b]$.

## **Teo** Discontinuidades finitas
Si $f$ es contínua en $[a.b]$ excepto en una cantidad finita de puntos (discontinuidades finitas) entonces $f$ es integrable en $[a,b]$.

## Sumas de Riemann

### **Def** Partición regular
Una partición de $[a,b]$ es **regular** si todos los subintervalos generados por la partición miden lo mismo. En ese caso, lo que mide cada intervalo es $\varDelta{x}=\frac{b-a}{n}$

### **Def** Sumas de Riemann
Sea $f$ acotada en $[a,b]$. Una **Suma de Riemann** de $f$ en $[a,b]$ es

$$
\begin{gathered}
\text{SR} = \sum_{i=1}^n f(c_i)\varDelta{x}
\end{gathered}
$$
donde $c_i$ es cualquier número en $[t_{i-1},t_i]$.

### **Teo** Sumas de Riemann e Integrales
Si $f$ es contínua en $[a,b]$ entonces

$$
\begin{gathered}
\int_{a}^{b} f(x)dx = \lim_{n \to \infty} \sum_{i=1}^{n} f(c_i)\varDelta{x} 
\end{gathered}
$$

#### **Obs**
En una partición regular $\varDelta{x} = \frac {b-a}{n}$  
**Extremo derecho** de cada subintervalo: $c_i = a + i\varDelta{x}$  
**Extremo izquierdo** de cada subintervalo: $c_i = a + (i-1)\varDelta{x}$

# Área bajo la curva

## **Def** Área bajo la curva
Sea $f:[a,b] \to \mathbb R$ integrable y $f(x) \ge 0 \implies$ que el área entre el eje $x$, la gráfica de $f$ y las rectas $x=a$ y $x=b$ se define como

$$
\begin{gathered}
\text{área} ( \mathbb R) = \int_{a}^{b}f(x)dx
\end{gathered}
$$

### **Corolario**
Si $f(x) \le 0$, definimos el área bajo el eje $x$, sobre la gráfica de $f$ y entre las rectoas $x=a$ y $x=b$ como

$$
\begin{gathered}
\text{área} = - \int_{a}^{b} f(x)dx
\end{gathered}
$$

# **Teo** Igualdad de funciones integrables
Si $f$ es contínua en $[a,b]$ y es una función definida en $[a,b] \text{t.q.} f(x) = g(x)$ excepto en un punto

$$
\begin{gathered}
\implies \int_{a}^{b} f(x)dx= \int_{a}^{b} g(x)dx
\end{gathered}
$$

# Propiedades de la Integral

1. $\int_{a}^{a} f(x)dx = 0$
2. $\int_{a}^b f(x)dx = - \int_{b}^a f(x)dx$
3. $\int_{a}^b kf(x)dx = k\int_{a}^b f(x)dx$
4. $\int_{a}^b(f(x)+g(x))dx = \int_{a}^{b}f(x)dx + \int_{a}^{b}g(x)dx$
5. $\int_{a}^b(f(x)-g(x))dx = \int_{a}^{b}f(x)dx - \int_{a}^{b}g(x)dx$
6. $f$ es integrable en $[a,b]$ y en $[b,c] \iff$ $f$ es integrabe en $[a,c]$ y además

$$
\begin{gathered}
\int_{a}^c f(x)dx = \int_{a}^b f(x)dx + \int_{b}^c f(x)dx
\end{gathered}
$$

# Teorema Fundamental del Cálculo

## **Teo** T. F. C. Parte 1
Sea $f$ contínua en $[a,b]$. Entonces, $F(x) = \int_a^xf(t)dt$ es contínua en $[a,b]$ y derivable en $[a,b]$ y además

$$
\begin{gathered}
F'(x) =  f(x)\\
\frac{d}{dx} (\int_a^x f(t)dt) = f(x)
\end{gathered}
$$

## **Teo** T. F. C. Parte 2
Si una función es contínua en $[a,b]$, entonces

$$
\begin{gathered}
\int_{a}^b f(x)dx = F(b)-F(a)
\end{gathered}
$$
donde 

$$
\begin{gathered}
F(x)'=f(x) \\
\forall x \in [a,b]
\end{gathered}
$$

# **Def** Integral Indefinida (antiderivada)
Una función $F$ es una **antiderivada** de $f$ en un intérvalo $I$ si

$$
\begin{gathered}
F'(x) = f(x)\\
\forall x \in I
\end{gathered}
$$

## **Teo** Igualdad de antiderivadas
Si $F$ es una antiderivada de $f$ en un intervalo $I$, entonces $G$ es otra antiderivada de $f \iff G(x) = F(x)+c$

# Lista de antiderivadas
1. $\int 0 dx = c$
2. $\int x^n dx = \frac{x^{n+1}} {n+1} + c$
3. $\int \cos(x) dx = \sin(x) +c$
4. $\int \sec^2(x) dx = \tan(x) +c$
5. $\int \csc^2(x) dx = -\cot(x) +c$
6. $\int \sec(x)\tan(x) dx = \sec(x) +c$
7. $\int \csc(x)\cot(x) dx = -\csc(x) +c$

# Cotas

## **Teo**
Sea $f$ contínua en $[a,b] \text{ t.q. } m\le f(x) \le M \forall x \in [a,b] \iff m(b-a) \le \int_{a}^{b} f(x)dx \le M(b-a)$

### **Corolario**
Sea $f(x) \ge 0$ y contínua en $[a,b]$. Entonces, $\int_{a}^b f(x)dx \ge 0$

### **Corolario**
Sean $f$ y $g$ funciones contínuas $\text{t.q. } \forall x \in [a,b],f(x) \le g(x)$ entonces, $\int_a^b f(x) dx \le \int_a^b g(x)dx$

## **Teo** Teorema del Valor Medio para Integrales
Si $f$ es contínua en el intervalo cerrado $[a,b] \implies$ existe un número $c \in [a,b]$ tal que

$$
\begin{gathered}
f(c)(b-a) = \int_a^b f(x)dx
\end{gathered}
$$

## Composición de Funciones en Integrales
En general,

$$
\begin{gathered}
F(g(x)) = \int_{a}^{g(x)} f(t) dt
\end{gathered}
$$

## **Teo** Regla de Leibinz
Sea $f$ contínua en $[a,b]$ y $g(x),h(x)$ funciones derivables de $x \in [a,b]$. Entonces,

$$
\begin{gathered}
\frac{dx}{d} \int_{g(x)}^{h(x)} f(t)dt = f(h(x))h'(x) - f(g(x))g'(x)
\end{gathered}
$$

# Diferenciales

## Def
Se denota al **diferencial** de $x$ como $dx = \varDelta x$ y al **diferencial** de $y$ como $dy = f'(x)dx$. 

## Reglas para diferenciales
Sean $u = f(x), v=g(x)$ funciones diferenciables de $x$($\therefore du=f(x)dx, dv=g(x)dx$).   
Entonces,

1. $d(u+v) = du + dv$
2. $d(uv) = du(v) + u(dv)$
3. $d(\frac{v}{u}) = \frac{du(v)-u(dv)}{v^2}$

# Integración por substitución (cambio de variable)

## Recordar

$$
\begin{gathered}
u = g(x) \implies du = g'(x)
\end{gathered}
$$

## **Teo** Integración y $u$ y $du$
Si $u=g(s)$ es una función derivable de $x$ cuyo rango es un intervalo $I$, y $f$ es contínua sobre $I$, entonces

$$
\begin{gathered}
\int f(g(x))g'(x) dx = \int f(u)du
\end{gathered}
$$

# Logaritmo Natural

## **Def**
Definimos a la función **logaritmo natural** de $x$, denotada como $\ln(x)$, como

$$
\begin{gathered}
\ln(x) = \int_{1}^{x} \frac{1}{t} dt, \forall x>0
\end{gathered}
$$

### Observación I
Por definición, $\text{Dom}(\ln(x)) = (0,\infty)$

### Observación II

$$
\begin{gathered}
\ln(1) = \int_{1}^{1} \frac{1}{t} dt = 0 \\
\therefore \ln(1) = 0
\end{gathered}
$$

### Observación III

$$
\begin{gathered}
\text{Si } x > 1 \implies ln(x) >0
\end{gathered}
$$

### Observación IV

$$
\begin{gathered}
\text{Si } 0< x < 1 \implies \ln(x) < 0
\end{gathered}
$$

## **Teo** Derivación ded $\ln(x)$ 
$ln(x)$ es contínua y derivable en $(0,\infty)$, y además, 

$$
\begin{gathered}
\frac{d}{dx} (ln(x)) = \frac{1}{x}
\end{gathered}
$$

### Observación
Usando la regla de la cadena

$$
\begin{gathered}
(\ln(u(x)))' = \frac{1}{u(x)} * u'(x) = \frac{u'(x)}{u(x)}
\end{gathered}
$$
