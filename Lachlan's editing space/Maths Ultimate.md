---
tags:
  - maths
  - mathematics
---
# Tasks
## Advanced
### Term 1:
#### MA-F2 Graphing Techniques
##### Outcomes:
- Uses detailed algebraic and graphical techniques to critically construct, model and evaluate arguments in a range of familiar and unfamiliar contexts (MA12-1)
- Chooses and uses appropriate technology effectively in a range of contexts, models and applies critical thinking to recognise appropriate times for such use (MA12-9)
- Constructs arguments to prove and justify results and provides reasoning to support conclusions which are appropriate to the context (MA12-10)
##### Subtopic focus:
The principle focus of this subtopic is to become more familiar with key features of graphs and functions, as well as develop an understanding of and use of the effect of basic transformations of these graphs to explain graphical behaviour
Students develop an understanding of transformations from a graphical and algebraic approach, including the use of technology, and thus develop a deeper understanding of the properties of functions. As graphing software becomes more widely accessible, skills in reading scales and interpreting magnification effects becomes essential.
##### Syllabus content:
- Apply transformations to sketch functions of the form $y=kf(a(x+b))+c$, where $f(x)$ is a polynomial, reciprocal, absolute value, exponential or logarithmic function, and a, b, c and k are constants
	- Examine translations and the graphs of $y=f(x)+c$ and $y=f(x+b)$ using technology
	- Examine dilations and the graphs of $y=kf(x)$ and $y=f(ax)$ using technology
	- Recognise that the order in which transformations are applied is important in the construction of the resulting function or graph
###### Transformations of functions & graphs
***Dilation before translation***. Order of vertical and horizontal doesn't matter.
Function f(x) is vertically dilated by factor k, then translated by c ($y=k\times{f(x)}+c$) 
Function f(x) is is horizontally dilated by a factor of $\frac{1}{a}$, then shifted by $-b$ units. NOTE: a is factored ($y=f(a(x+b))$)
Combined together, $y=kf(a(x+b))+c$ : Vertical dilation by $k$, horizontal dilation by $\frac{1}{a}$, shifted direction opposite to the sign of $b$, shifted up or down by $c$.
The vertical dilation stretches the graph, easily visualised by changing the turning points from a point, say $(x, y)$ to $(x,ky)$. 

Horizontal dilation (compression): ![[Pasted image 20231112132808.png|373]]

- Use graphical methods with supporting algebraic working to solve a variety of practical problems involving any of the functions within the scope of this syllabus, in both real-life and abstract contexts
	- Select and use an appropriate method to graph a given function, including finding intercepts, considering the sign of $f(x)$ and using symmetry
	- Determine asymptotes and discontinuities where appropriate (vertical and horizontal asymptotes only)
	- Determine the number of solutions of an equation by considering appropriate graphs
	- Solve linear and quadratic inequalities by sketching appropriate graphs

#### MA-T3 Trigonometric Functions and Graphs
#### MA-C2 Differential Calculus

## Extension
### Term 1
#### ME-P1 Proof by Mathematical Induction
##### Outcomes:
- Applies techniques involving proof or calculus to model and solve problems (ME12-1)
- Chooses and uses appropriate technology to solve problems in a range of contexts (ME12-6)
- Evaluates and justifies conclusions, communicating a position clearly in appropriate mathematical forms (ME12-7)
##### Subtopic Focus:
The principle focus of this subtopic is to explore and to 

#### ME-T3 Trigonometric Equations
#### ME-C2 Further Calculus Skills
# Calculus
#calculus
## Logarithmic calculus

$g(x)=a^{f(x)}$
$g'(x)=ln_a*f'(x)*a^{f(x)}$

Differentiate $y=x^x$
Take natural log of both sides: $\ln{y}=\ln{x^x}$
Use log law to take power out front: $\ln{y}=x\ln{x}$
Differentiate both sides: $\frac{y'}{y}=\frac{d}{dx}x\ln{x}$
= $\frac{y'}{y}=x\frac{1}{x}+\ln{x}$
Multiply by y to make y' the subject: $y'=y(x\frac{1}{x}+\ln{x})$
sub in the value for y: $y'=x^x(x\frac{1}{x}+\ln{x})$
Simplify: $y'=x^x+x^x\ln{x}$

# Functions
#functions

## Solving Equations

When solving equations, there are normally two main methods:
### Algebraic solving

### Graphical solving
When solving $f(x)=g(x)$:
- the number of solutions is the number of points of intersection of $y=f(x)$ and $y=g(x)$.
- The solutions are the $x$-values of the points of intersection
When solving $f(x)>g(x)$:
- the range of $x$-values where $y=f(x)$ is above $y=g(x)$
$f(x)<g(x)$
- the range of $x$-values where $y=f(x)$ is below $y=g(x)$

## Transformations of functions & graphs
***Dilation before translation***. Order of vertical and horizontal doesn't matter.
Function f(x) is vertically dilated by factor k, then translated by c ($y=k\times{f(x)}+c$) 
Function f(x) is is horizontally dilated by a factor of $\frac{1}{a}$, then shifted by $-b$ units. NOTE: a is factored ($y=f(a(x+b))$)
Combined together, $y=kf(a(x+b))+c$ : Vertical dilation by $k$, horizontal dilation by $\frac{1}{a}$, shifted direction opposite to the sign of $b$, shifted up or down by $c$.
### Asymptotes of graphs:
#asymptotes
$y$-intercepts when $x=0$
$x$-intercepts when $y=0$
Consider the equation: $$h(x)=\frac{g(x)}{f(x)}$$
Vertical asymptotes where denominator $f(x)=0$
Horizontal asymptotes are found through **limiting behaviour**, $\lim \limits_{x \to \infty} f(x)$, divide throughout $h(x)$ by highest power in $f(x)$. p
Test if the function is even by subbing in $f(-x)$

#### Examples:
- horizontal:
	$f(x)=\frac{2^x+1}{2^x-1}$
	as $x$⇒-∞, $2^x+1$ --> 1 & $2^x-1$ -> -1
	horizontal:
	$f(x)=\frac{\sqrt{16x^2-8}}{2x-5}$
	Divide throughout by 1/x
	=$\frac{\sqrt{(16x^2-8)*\frac{1^2}{x^2}}}{2-\frac{5}{x}}$
	=$\frac{\sqrt{16-0}}{2-0}$
	=$\frac{4}{2}$
	=2
	∴horizontal asymptote at y=2 for positive values of x

# Trigonometry
To graph, use caps
$f(x)=ksin(b(x+c))+d$
C: Centre ($d$)
A: Amplitude ($|k|$)
P: Period ($\frac{2π}{b}$ if sin/cos, $\frac{π}{b}$ if tan)
S: shift ($-c$ units)

Solving trig eqns:
$y=sin(x)$
RAA: related acute angle, $sin^-1(|y|)$ - then find quadrants using ASTC (all positive, sin positive, cos positive, tan positive)
Simplify equations initially before working on 




Vertical:
$f(x)=\frac{x}{x^2-4}$
= $\frac{x}{(x+2)(x-2)}$
∴asymptotes at x=±2, as denominator ≠ 0
DISREGARD vertical:
divide by the highest power in denominator
$f(x)=\frac{x}{x^2-4}$
$÷x^2$
=$\frac{\frac{x}{x^2}}{\frac{x^2}{x^2}-\frac{4}{x^2}}$
=$\frac{\frac{1}{x}}{1-\frac{4}{x^2}}$
as $x$ becomes bigger, 1/x becomes smaller. Same with $4/x^2$
apply a limit as x approaches 0:
= $\lim \limits_{x\to\infty}$ , $\frac{1}{x} \rightarrow 0$
= $\frac{0}{1-0}$
=$0$
Whenever there is a power on the bottom of the fraction larger than the top, doing the above process will always result in 0


