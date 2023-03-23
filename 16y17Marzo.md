# Calculo Integral
## Ejercicios Integración por partes
Intente llegar a la respuesta correcta con las pistas que se encuentran en el enunciado, Puedes revisar la respuesta de los ejercicios en las paginas finales:
### Ejercicio 1
Integra $\int x \ln x dx$.\
Pista: Se utiliza $u=\ln x$, $du=\frac{1}{x}dx$\
a) $\frac{1}{2} x^2 \ln x - \frac{1}{4} x^2$\
b) $\frac{1}{2} x^2 \ln x - \frac{1}{2} x^2$\
c) $\frac{1}{2} x^2 \ln x - x^2$\
d) $\frac{1}{2} x^2 \ln x - 2x^2$

### Ejercicio 2
Integra $\int \cos^2 x dx$:\
Pista: Se utiliza $u=\cos x$, $du=-\sin x dx$\
a) $\frac{1}{2} x + \frac{1}{4} \sin 2x$\\
b) $\frac{1}{2} x + \frac{1}{2} \sin 2x$\\
c) $\frac{1}{2} x - \frac{1}{4} \sin 2x$\\
d) $\frac{1}{2} x - \frac{1}{2} \sin 2x$

### Ejercicio 3
Integra $\int e^x \sin x dx$.\
Pista: Se utiliza $u = x$ y $dv = \cos(x)dx$\
a) $\frac{1}{2} e^x (\sin x - \cos x) + C$
b) $\frac{1}{2} e^x (\sin x + \cos x) + C$
c) $-\frac{1}{2} e^x (\sin x - \cos x) + C$
d) $-\frac{1}{2} e^x (\sin x + \cos x) + C$


### Ejercicio 4
Integre $\int x \cos(x) dx$
Pista: $u=x$ y $dv=\cos(x)dx$
a) $x\sin(x) + \cos(x) + C$
b) $\frac{1}{2}x\sin(x) - \frac{1}{2}\cos(x) + C$
c) $\frac{1}{2}x\sin(x) + \frac{1}{2}\cos(x) + C$
d) $x\sin(x) - \cos(x) + C$

### Ejercicio 5
Evalúe $\int \ln(x)dx$ 
Pista: 
a) $x\ln(x) - x + C$
b) $x\ln(x) + x + C$
c) $x\ln(x) - \frac{1}{2}x^2 + C$
d) $\frac{1}{2}x^2 \ln(x) - \frac{1}{4}x^2 + C$

### Ejercicio 6
Evalúe $\int x^2 e^x dx$ 
a) $x^2 e^x - 2xe^x + 2e^x + C$
b) $x^2 e^x - xe^x + e^x + C$
c) $x^2 e^x + xe^x - e^x + C$
d) $x^2 e^x + 2xe^x - 2e^x + C$

## Solución
### Ejercicio 1
Respuesta correcta: b) $\frac{1}{2} x^2 \ln x - \frac{1}{2} x^2$

Realimentación:

Se utiliza $u=\ln x$, $du=\frac{1}{x}dx$, $dv=x dx$, $v=\frac{1}{2} x^2$.

$$\int x \ln x dx = \frac{1}{2} x^2 \ln x - \int \frac{1}{2} x dx = \frac{1}{2} x^2 \ln x - \frac{1}{4} x^2 + C$$

### Ejercicio 2
Respuesta correcta: a) $\frac{1}{2} x + \frac{1}{4} \sin 2x$

Explicación:
Se utiliza $u=\cos x$, $du=-\sin x dx$, $dv=\cos x dx$, $v=\sin x$.

$$\int \cos^2 x dx = \sin x \cos x - \int \sin^2 x dx = \frac{1}{2} \sin 2x + \frac{1}{2} x + C$$

### Ejercicio 3
Respuesta correcta: c) $-\frac{1}{2} e^x (\sin x - \cos x) + C$

Explicación:
Se utiliza $u=\sin x$, $du=\cos x dx$, $dv=e^x dx$, $v=e^x$.

$$\int e^x \sin x dx = e^x \sin x - \int e^x \cos x dx $$ $$= e^x \sin x - \frac{1}{2} e^x \cos x - C = -\frac{1}{2} e^x (\sin x - \cos x) + C$$

### Ejercicio 4
Respuesta correcta: c)
Tomamos $u=x$ y $dv=\cos(x)dx$, entonces $du=dx$ y $v=\sin(x)$, y aplicamos la fórmula de integración por partes:
$$\int x\cos(x)dx=x\sin(x)-\int \sin(x)dx=x\sin(x)+\cos(x)+C$$

### Ejercicio 5
Respuesta correcta: a)
Tomamos $u=\ln(x)$ y $dv=dx$, entonces $du=\frac{1}{x}dx$ y $v=x$, y aplicamos la fórmula de integración por partes:

$$\int \ln(x)dx=x\ln(x)-\int x \frac{1}{x} dx=x\ln(x)-x+C$$

### Ejercicio 6
Respuesta correcta: d)
Tomamos $u=x^2$ y $dv=e^x dx$, entonces $du=2xdx$ y $v=e^x$, y aplicamos la fórmula de integración por partes:

$$\int x^2 e^x dx=x^2 e^x -\int 2xe^x dx=x^2 e^x -2xe^x +2\int e^x dx=x^2 e^x +2xe^x -2e^x +C$$

