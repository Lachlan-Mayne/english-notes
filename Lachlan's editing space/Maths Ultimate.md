# Maths: Differentiating Logarithmically

Differentiate $y=x^x$
Take natural log of both sides: $\ln{y}=\ln{x^x}$
Use log law to take power out front: $\ln{y}=x\ln{x}$
Differentiate both sides: $\frac{y'}{y}=\frac{d}{dx}x\ln{x}$
= $\frac{y'}{y}=x\frac{1}{x}+\ln{x}$
Multiply by y to make y' the subject: $y'=y(x\frac{1}{x}+\ln{x})$
sub in the value for y: $y'=x^x(x\frac{1}{x}+\ln{x})$
Simplify: $y'=x^x+x^x\ln{x}$

### Transformations of functions & graphs
***Dilation before translation***. Order of vertical and horizontal doesn't matter.
Function f(x) is vertically dilated by factor k, then translated by c ($y=k\times{f(x)}+c$) 
Function f(x) is is horizontally dilated by a factor of $\frac{1}{a}$, then shifted by $-b$ units. NOTE: a is factored ($y=f(a(x+b))$)
Combined together, $y=kf(a(x+b))+c$: Vertical dilation by $k$, horizontal dilation by $\frac{1}{a}$, shifted direction opposite to the sign of $b$, shifted up or down by $c$.
#### Asymptotes of graphs:
$y$-intercepts when $x=0$
$x$-intercepts when $y=0$
Consider the equation: $$h(x)=\frac{g(x)}{f(x)}$$
Vertical asymptotes where denominator $f(x)=0$
Horizontal asymptotes are found through **limiting behaviour**, $\lim \limits_{x \to \infty} f(x)$, divide throughout $h(x)$ by highest power in $f(x)$. 
Test if the function is even by subbing in $f(-x)$