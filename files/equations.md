[Syntax](syntax.md) | [Terms](terms.md) | [Equations](equations.md) | [Horn formulas](horn_formulas.md) | [Universal formulas](universal_formulas.md) | [First-order formulas](first-order_formulas.md) | [Theories](theories.md)

Here we list equations, with the shorter term on the right (if possible).

|1  |trivial equations:  | $x= y$ $\quad f(x) = y$ $\quad x*y = z$  | $\Rightarrow$ one-element algebras  ||
|2  |identity operation:  | $f(x) = x$  |||
|3  |involutive operation:  | $f(f(x)) = x$  |||
|4  |inverse operations:  | $f(g(x)) = x$  |||
|5  |inside absorption:  | $f(g(x)) = f(x)$  |||
|6  |outside absorption:  | $f(g(x)) = g(x)$  |||
|7  |order-$n$ operation:  | $f^n(x) = x$  |||
|8  |$f$-idempotent  | $f(f(x)) = f(x)$  |||
|9  |constant operations:  | $f(x) = 1$ $\quad f(x) = f(y)$ $\quad x*y = 1$  | $x*y = f(z)$  | $x*y = z*w$  |
|10  |left projection:  | $x*y = x$  | right projection:  | $x*y = y$  |
|11  |idempotent:  | $x*x = x$  |||
|12  |$n$-potent:  | $x^{n+1} = x^n$  |||
|13  |left identity:  | $1*x = x$  | right identity:  | $x*1 = x$  |
|14  |left zero:  | $0*x = 0$  | right zero:  | $x*0 = 0$  |
|15  |left $f$-projection:  | $x*y = f(x)$  | right $f$-projection:  | $x*y = f(y)$  |
|16  |square constant:  | $x*x = 1$  |||
|17  |square definition:  | $x*x = f(x)$  |||
|18  |left constant multiple:  | $1*x = f(x)$  | right constant multiple:  | $x*1 = f(x)$  |
|19  |commutative:  | $x*y = y*x$  |||
|20  |left inverse:  | $f(x)*x = 1$  | right inverse:  | $x*f(x) = 1$  |
|21  |left $f$-identity:  | $f(x)*x = x$  | right $f$-identity:  | $x*f(x) = x$  |
|22  |interassociative:  | $x*(y+z) = (x+y)*z$  |||
|23  |associative:  | $x*(y*z) = (x*y)*z$  |||
|24  |left commutativity:  | $x*(y*z) = y*(x*z)$  | right commutativity:  | $(x*y)*z = (x*z)*y$  |
|25  |left idempotent:  | $x*(x*y) = x*y$  | right idempotent:  | $(x*y)*y = x*y$  |
|26  |left rectangular:  | $(x*y)*x = x$  | right rectangular:  | $x*(y*x) = x$  |
|27  |left absorption:  | $(x*y)+x = x$  | right absorption:  | $x+(y*x) = x$  |
|28  |left absorption1:  | $(x*y)+y = y$  | right absorption1:  | $y+(x*y) = y$  |
|29  |left subtraction:  | $x*(x+y) = y$  | right subtraction:  | $(y+x)*x = y$  |
|30  |left distributive:  | $x*(y+z) = (x*y)+(x*z)$  | right distributive:  | $(x+y)*z = (x*z)+(y*z)$  |
|31  |left self-distributive:  | $x*(y*z) = (x*y)*(x*z)$  | right distributive:  | $(x*y)*z = (x*z)*(y*z)$  |
|32  |$f$-commutative:  | $f(x)*f(y) = f(y)*f(x)$  |||
|33  |$f$-involutive:  | $f(x*y) = f(y)*f(x)$  |||
|34  |$f$-interdistributive:  | $f(x*y) = f(x)+f(y)$  |||
|35  |$f$-distributive:  | $f(x*y) = f(x)*f(y)$  | also $f$-linear  ||
|36  |left $f$-constant multiple:  | $f(1*x) = 1*f(x)$  | right $f$-constant multiple:  | $f(x*1) = f(x)*1$  |
|37  |left twisted:  | $f(x*y)*x = x*f(y)$  | right twisted:  | $x*f(y*x) = f(y)*x$  |
|38  |left locality:  | $f(f(x)*y) = f(x*y)$  | right locality:  | $f(x*f(y)) = f(x*y)$  |
|39  |left $f$-distributive:  | $f(f(x)*y) = f(x)*f(y)$  | right $f$-distributive:  | $f(x*f(y)) = f(x)*f(y)$  |
|40  |left $f$-absorbtive:  | $f(x)*f(x*y) = f(x*y)$  | right $f$-absorbtive:  | $f(x*y)*f(y)) = f(x*y)$  |
|41  |flexible:  | $(x*y)*x = x*(y*x)$  |||
|42  |entropic:  | $(x*y)*(z*w) = (x*z)*(y*w)$  |||
|43  |paramedial:  | $(x*y)*(z*w) = (w*y)*(z*x)$  |||
|44  |Moufang1:  | $((x*y)*x)*z = x*(y*(x*z))$  | Moufang2:  | $((x*y)*z)*y = x*(y*(z*y))$  |
|45  |Moufang3:  | $(x*y)*(z*x) = (x*(y*z))*x$  | Moufang4:  | $(x*y)*(z*x) = x*((y*z)*x)$  |

Here are the identities in the syntax of the Lean Theorem Prover 

<code>
section identities

variables {α: Type u} {β: Type v}
variables f g: α → α → α
variables h k: α → α
variable  c: α
local notation a⬝b  := f a b
local notation a+b := g a b
local notation a⁻¹ := h a
local notation 1   := c
local notation 0   := c

def involutive              := ∀x,     h(h x) = x
def inverse_operations      := ∀x,     h(k x) = x
def left_absorption         := ∀x,     h(k x) = k x
def right_absorption        := ∀x,     h(k x) = h x
def unary_idempotent        := ∀x,     h(h x) = h x
def idempotent              := ∀x,     x⬝x = x
def left_identity           := ∀x,     1⬝x = x
def right_identity          := ∀x,     x⬝1 = x
def left_zero               := ∀x,     0⬝x = 0
def right_zero              := ∀x,     x⬝0 = 0
def left_inverse            := ∀x,     x⁻¹⬝x = 1
def right_inverse           := ∀x,     x⬝x⁻¹ = 1
def left_const_mult         := ∀x,     c⬝x = h x
def right_const_mult        := ∀x,     x⬝c = h x
def square_constant         := ∀x,     x⬝x = c
def square_unary            := ∀x,     x⬝x = h x
def left_unary_identity     := ∀x,     (h x)⬝x = x
def right_unary_identity    := ∀x,     x⬝(h x) = x
def left_unary_const_mult   := ∀x,     h(c⬝x) = c⬝(h x)
def right_unary_const_mult  := ∀x,     h(x⬝c) = (h x)⬝c
def commutative             := ∀x y,   x⬝y = y⬝x
def left_unary_projection   := ∀x y,   x⬝y = h x
def right_unary_projection  := ∀x y,   x⬝y = h y
def left_idempotent         := ∀x y,   x⬝(x⬝y) = x⬝y
def right_idempotent        := ∀x y,   (x⬝y)⬝y = x⬝y
def left_rectangular        := ∀x y,   (x⬝y)⬝x = x
def right_rectangular       := ∀x y,   x⬝(y⬝x) = x
def left_absorption1        := ∀x y,   (x⬝y)+y = y
def right_absorption1       := ∀x y,   y+(x⬝y) = y
def left_absorption2        := ∀x y,   (x⬝y)+x = x
def right_absorption2       := ∀x y,   x+(y⬝x) = x
def left_subtraction        := ∀x y,   x⬝(x+y) = y
def right_subtraction       := ∀x y,   (y+x)⬝x = y
def unary_commutative       := ∀x y,   (h x)⬝(h y) = (h y)⬝(h x)
def unary_involutive        := ∀x y,   h(x⬝y) = (h y)⬝(h x)
def interdistributive       := ∀x y,   h(x⬝y) = (h x)+(h y)
def unary_distributive      := ∀x y,   h(x⬝y) = (h x)⬝(h y) 
def left_twisted            := ∀x y,   (h(x⬝y))⬝x = x⬝(h y) 
def right_twisted           := ∀x y,   x⬝(h(y⬝x)) = (h y)⬝x
def left_locality           := ∀x y,   h((h x)⬝y) = h(x⬝y)
def right_locality          := ∀x y,   h(x⬝(h y)) = h(x⬝y)
def left_unary_distributive := ∀x y,   h((h x)⬝y) = (h x)⬝(h y)
def right_unary_distributive:= ∀x y,   h(x⬝(h y)) = (h x)⬝(h y)
def left_absorbtive         := ∀x y,   (h x)⬝(h(x⬝y)) = h(x⬝y)
def right_absorbtive        := ∀x y,   (h(x⬝y))⬝(h y) = h(x⬝y)
def flexible                := ∀x y,   (x⬝y)⬝x = x⬝(y⬝x)
def associative             := ∀x y z, x⬝(y⬝z) = (x⬝y)⬝z
def left_commutative        := ∀x y z, x⬝(y⬝z) = y⬝(x⬝z)
def right_commutative       := ∀x y z, (x⬝y)⬝z = (x⬝z)⬝y
def interassociative1       := ∀x y z, x⬝(y+z) = (x⬝y)+z
def interassociative2       := ∀x y z, x⬝(y+z) = (x+y)⬝z
def left_distributive       := ∀x y z, x⬝(y+z) = (x⬝y)+(x⬝z)
def right_distributive      := ∀x y z, (x+y)⬝z = (x⬝z)+(y⬝z)
def left_self_distributive  := ∀x y z, x⬝(y⬝z) = (x⬝y)⬝(x⬝z)
def right_self_distributive := ∀x y z, (x⬝y)⬝z = (x⬝z)⬝(y⬝z)
def Moufang1                := ∀x y z, ((x⬝y)⬝x)⬝z = x⬝(y⬝(x⬝z))
def Moufang2                := ∀x y z, ((x⬝y)⬝z)⬝y = x⬝(y⬝(z⬝y))
def Moufang3                := ∀x y z, (x⬝y)⬝(z⬝x) = (x⬝(y⬝z))⬝x
def Moufang4                := ∀x y z, (x⬝y)⬝(z⬝x) = x⬝((y⬝z)⬝x)
def entropic                := ∀x y z w, (x⬝y)⬝(z⬝w) = (x⬝z)⬝(y⬝w)
def paramedial              := ∀x y z w, (x⬝y)⬝(z⬝w) = (w⬝y)⬝(z⬝x)


end identities
</code>