# Mathematical Questions using Python

## Question 1.6
Show that $$\\sin({\\frac{2 \\pi}{10}}) + \\sin({\\frac{4 \\pi}{10}}) + \\dots + \\sin({\\frac{10 \\pi}{10}}) = \\sqrt{\\frac{1}{2}(5 - \\sqrt{5})} + \\sqrt{\\frac{1}{2}(5 + \\sqrt{5})}$$

Lets say LHS = $\\sin({\\frac{2 \\pi}{10}}) + \\sin({\\frac{4 \\pi}{10}}) + \\dots + \\sin({\\frac{10 \\pi}{10}})$ and RHS = $\\sqrt{\\frac{1}{2}(5 - \\sqrt{5})} + \\sqrt{\\frac{1}{2}(5 + \\sqrt{5})}$


## Question 4.10
Using functional programming, demonstrate that for any sequence of positive numbers $a_1,a_2, \\dots, a_n$ we have $$(a_1 + a_2 + \\dots + a_n) (\\frac{1}{a_1} + \\frac{1}{a_2} + \\dots + \\frac{1}{a_n}) \\geq n^2$$


## Question 6.4
Consider the following functions of two variables $$x(u,v) = \\sin{(v)} \\cos{(u)}$$ $$y(u,v) = \\sin{(v)} \\sin{(u)}$$ $$z(u,v) = \\cos{(v)}$$ 

Generate the surface $(x, y, z)$ when $0 \\leq u \\leq \\frac{3\\pi}{2}$ and $0 \\leq v \\leq \\pi$. 

Now consider $x_1(u,v) = \\frac{-3}{8} \\cos{(v)} \\sin{(\\frac{4u}{3})}$, $y_1(u,v)= \\frac{3}{8}\\cos{(\\frac{4u}{3})}\\cos{(v)}$  and $z_1(u,v) = -\\frac{\\sin{(v)}}{2}$. Generate the surface $$(\\frac{dx_1}{dvdu}, \\frac{dy_1}{dudv}, \\frac{dz_1}{dv})$$ when $0 \\leq u \\leq \\frac{3\\pi}{2}$ and $0 \\leq v \\leq \\pi$. Finally, superimpose these two images.


## Question 7.5
Consider a $10 \\times 10$ matrix with positve integer numbers as its entries. Write a function $\\theta$ which is the sum of the third largest number of each row.

Now create a $10 \\times 10$ matrix $M$ with entry numbers are $1$ to $100$:

$$M = \\begin{pmatrix} 1 & 2 & \\dots & 10 \\\\ 11 & 12 & \\dots & 20 \\\\ \\vdots & \\vdots & \\vdots & \\vdots \\\\ 91 & 92 & \\dots & 100 \\\\ \\end{pmatrix}$$

Show $\\theta(M)$ is greater than the sum of the numbers in some row.


## Question 8.2
Plot a graph of the expression $$\\sum_{n=1}^{50} \\frac{\\sin{nx}}{n}$$ for $0 \\leq x \\leq 2\\pi$.
