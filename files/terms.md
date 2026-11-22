[Syntax](syntax.md) | [Terms](terms.md) | [Equations](equations.md) | [Horn formulas](horn_formulas.md) | [Universal formulas](universal_formulas.md) | [First-order formulas](first-order_formulas.md) | [Theories](theories.md)

Here we list distinct terms with no constant subterms other than $0, 1$.

Any variables, constant symbols or operation symbols can be substituted instead of $x$ $y$ $z$ $w$ $1$ $f$ $g$ $*$ $+$ $-$ respectively.

### = Terms of depth 0 =

$x$

### = Terms of depth 1 =

$f(x) \qquad x*y \qquad x*x \qquad 1*x \qquad x*1$

### = Terms of depth 2 =

$f(g(x)) \qquad f(f(x)) \qquad f(x*y) \qquad f(x*x) \qquad f(1*x) \qquad f(x*1) \qquad f(x)*y \qquad f(x)*x \qquad$ 
$f(x)*1 \qquad x*f(y) \qquad x*f(x) \qquad 1*f(x) \qquad f(x)*g(y) \qquad f(x)*g(x) \qquad f(x)*f(y) \qquad f(x)*f(x) \qquad$ 16 terms

$x*(y+z) \qquad x*(x+y) \qquad x*(y+x) \qquad y*(x+x) \qquad x*(x+x) \qquad x*(y+1) \qquad x*(1+y) \qquad 1*(x+y) \qquad x*(x+1) \qquad x*(1+x) \qquad$ $1*(x+x) \qquad 0*(x+1) \qquad 0*(1+x) \qquad 1*(x+1) \qquad 1*(1+x) \qquad$ 15 terms

$(x*y)+z \qquad (x*x)+y \qquad (x*y)+x \qquad (y*x)+x \qquad (x*x)+x \qquad (x*y)+1 \qquad (x*1)+y \qquad (1*x)+y \qquad (x*x)+1 \qquad (x*1)+x \qquad$ $(1*x)+x \qquad (x*0)+1 \qquad (0*x)+1 \qquad (x*1)+1 \qquad (1*x)+1 \qquad$ 15 terms

$x*(y*z) \qquad x*(x*y) \qquad x*(y*x) \qquad y*(x*x) \qquad x*(x*x) \qquad x*(y*1) \qquad x*(1*y) \qquad 1*(x*y) \qquad x*(x*1) \qquad x*(1*x) \qquad$ $1*(x*x) \qquad 0*(x*1) \qquad 0*(1*x) \qquad 1*(x*1) \qquad 1*(1*x) \qquad$ 15 terms

$(x*y)*z \qquad (x*x)*y \qquad (x*y)*x \qquad (y*x)*x \qquad (x*x)*x \qquad (x*y)*1 \qquad (x*1)*y \qquad (1*x)*y \qquad (x*x)*1 \qquad (x*1)*x \qquad$ $(1*x)*x \qquad (x*0)*1 \qquad (0*x)*1 \qquad (x*1)*1 \qquad (1*x)*1 \qquad$ 15 terms

$f(x)*(y+z) \qquad f(x)*(x+y) \qquad f(x)*(y+x) \qquad f(y)*(x+x) \qquad f(x)*(x+x) \qquad f(x)*(y+1) \qquad f(x)*(1+y) \qquad f(x)*(x+1) \qquad f(x)*(1+x) \qquad$ 9 terms

$(x*y)+f(z) \qquad (x*x)+f(y) \qquad (x*y)+f(x) \qquad (y*x)+f(x) \qquad (x*x)+f(x) \qquad (x*1)+f(y) \qquad (1*x)+f(y) \qquad (x*1)+f(x) \qquad (1*x)+f(x) \qquad$ 9 terms

$f(x)*(y*z) \qquad f(x)*(x*y) \qquad f(x)*(y*x) \qquad f(y)*(x*x) \qquad f(x)*(x*x) \qquad f(x)*(y*1) \qquad f(x)*(1*y) \qquad f(x)*(x*1) \qquad f(x)*(1*x) \qquad$ 9 terms

$(x*y)*f(z) \qquad (x*x)*f(y) \qquad (x*y)*f(x) \qquad (y*x)*f(x) \qquad (x*x)*f(x) \qquad (x*1)*f(y) \qquad (1*x)*f(y) \qquad (x*1)*f(x) \qquad (1*x)*f(x) \qquad$ 9 terms

$(x*y)+(z-w)$ and all substitution instances with $x$ $y$ $z$ $1$ $*$ $+$

### = Terms of depth 3 =

Only terms of the form that actually occur in practice are listed below.

$f(f(x)*y) \qquad f(x*f(y)) \qquad f(f(x)*f(y))$

$f(f(x)*x) \qquad f(x*f(x)) \qquad f(f(x)*f(x))$

$(x*f(x))*x \qquad x*(f(x)*x)$

$((x*y)*x)*f((x*y)*x) \qquad (x*(y*x))*f(x*(y*x))$

$(x*f(x))*(y*f(y))$
