Calc Module 16: Improper Integrals & Probability Densities
----------------------------------------------------------

![Calculus Banner.svg](https://wustl-catalog.instructure.com/courses/254/files/25266/download)

### Topics Covered

*   Improper Integrals
*   Probability Density Functions (PDFs)

7.5 Improper Integrals
----------------------

✅  **Task:** Read Chapter 7.5 (pg. 305-309). Complete the following **exercises: 1, 9, 10, 15** (pg. 309) and compare your work to the solutions (where possible).

💡 **Tip**: If you get stuck on a concept or problem, ask a tutor or refer to the solution for a hint. Don’t spend too long getting hung up on one point!

8.4 Probability and Calculus
----------------------------

✅  **Task:** Read Chapter 8.4 (pg. 328-334) and complete the exercises below.

### Exercises

1.  With ![LaTeX: p_n = \frac{1}{2}^n](https://wustl.instructure.com/equation_images/p_n%2520%253D%2520%255Cfrac%257B1%257D%257B2%257D%255En?scale=1 "p_n = \frac{1}{2}^n") , what is the probability that ![LaTeX: X](https://wustl.instructure.com/equation_images/X?scale=1 "X") is odd? Why is ![LaTeX: p_n = \frac{1}{3}^n](https://wustl.instructure.com/equation_images/p_n%2520%253D%2520%255Cfrac%257B1%257D%257B3%257D%255En?scale=1 "p_n = \frac{1}{3}^n") an impossible set of probabilities? What multiple ![LaTeX: c(\frac{1}{3})^n](https://wustl.instructure.com/equation_images/c(%255Cfrac%257B1%257D%257B3%257D)%255En?scale=1 "c(\frac{1}{3})^n") is possible?
2.  Why is ![LaTeX: p(x) = e^{-2x}](https://wustl.instructure.com/equation_images/p(x)%2520%253D%2520e%255E%257B-2x%257D?scale=1 "p(x) = e^{-2x}") not an acceptable probability density for ![LaTeX: x \geq 0](https://wustl.instructure.com/equation_images/x%2520%255Cgeq%25200?scale=1 "x \geq 0")? Why is ![LaTeX: p(x) = 4e^{-2x}-e^{-x}](https://wustl.instructure.com/equation_images/p(x)%2520%253D%25204e%255E%257B-2x%257D-e%255E%257B-x%257D?scale=1 "p(x) = 4e^{-2x}-e^{-x}") not acceptable?
3.  Suppose ![LaTeX: X](https://wustl.instructure.com/equation_images/X?scale=1 "X") is a random Weibull variable — this means that it has a probability density of the form ![LaTeX: f_X(x)](https://wustl.instructure.com/equation_images/f_X(x)?scale=1 "f_X(x)") given below. Show that ![LaTeX: f_X](https://wustl.instructure.com/equation_images/f_X?scale=1 "f_X") is a valid probability density.
    *   ![LaTeX: f_X(x)= 
        \begin{cases} 
        \lambda px^{p-1} e^{-\lambda x^p}, \quad &x > 0,  \\
        0, &x \leq 0 
        \end{cases}](https://wustl.instructure.com/equation_images/f_X(x)%253D%2520%250A%255Cbegin%257Bcases%257D%2520%250A%255Clambda%2520px%255E%257Bp-1%257D%2520e%255E%257B-%255Clambda%2520x%255Ep%257D%252C%2520%255Cquad%2520%2526x%2520%253E%25200%252C%2520%2520%255C%255C%250A0%252C%2520%2526x%2520%255Cleq%25200%2520%250A%255Cend%257Bcases%257D?scale=1 "f_X(x)= 
        \begin{cases} 
        \lambda px^{p-1} e^{-\lambda x^p}, \quad &x > 0,  \\
        0, &x \leq 0 
        \end{cases}")
4.  Find the marginal density ![LaTeX: f_X(x) = \int_{-\infty}^\infty f_{XY}(x,y) \; dy](https://wustl.instructure.com/equation_images/f_X(x)%2520%253D%2520%255Cint_%257B-%255Cinfty%257D%255E%255Cinfty%2520f_%257BXY%257D(x%252Cy)%2520%255C%253B%2520dy?scale=1 "f_X(x) = \int_{-\infty}^\infty f_{XY}(x,y) \; dy") when we are given

![LaTeX: f_{XY}(x,y) = 
\begin{cases} 
x e^{-x(y+1)}, \qquad &x >0 \text{ and } y > 0 \\ 
0, &\text{otherwise} 
\end{cases}](https://wustl.instructure.com/equation_images/f_%257BXY%257D(x%252Cy)%2520%253D%2520%250A%255Cbegin%257Bcases%257D%2520%250Ax%2520e%255E%257B-x(y%252B1)%257D%252C%2520%255Cqquad%2520%2526x%2520%253E0%2520%255Ctext%257B%2520and%2520%257D%2520y%2520%253E%25200%2520%255C%255C%2520%250A0%252C%2520%2526%255Ctext%257Botherwise%257D%2520%250A%255Cend%257Bcases%257D?scale=1 "f_{XY}(x,y) = 
\begin{cases} 
x e^{-x(y+1)}, \qquad &x >0 \text{ and } y > 0 \\ 
0, &\text{otherwise} 
\end{cases}")