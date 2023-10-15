Calc Module 19: Integration of Multiple Variables & Joint Probability Distributions
-----------------------------------------------------------------------------------

![Calculus Banner.svg](https://wustl-catalog.instructure.com/courses/254/files/25266/download)

### Topics Covered

*   Integration of Multiple Variables
*   Joint Probability Distributions

Integrals of Multiple Variables
-------------------------------

✅  **Task:** Read Chapter 14.1 Double Integrals (p.521-p.526). Complete the following **exercises: 4, 29, 31** (pg. 526-527) and compare your work to the solutions (where possible).

✅  **Task:** Read Chapter 14.3 Triple Integrals (p.536-p.539). Complete the following **exercises: 3, 15** (pg. 540) and compare your work to the solutions (where possible).

Joint Probability Distributions
-------------------------------

So far, we’ve explored probability distributions of single random variables. Let's try one involving two random variables!

✅  **Task:** Complete the exercise below. You may find it helpful to reference Chapter 8.4 (pg. 328-334) or Chapter 14.1 (pg. 521-526) of Strang.

In probability theory, a stochastic or random process is defined as a sequence of random variables where the index of the sequence have interpretation in time. One such process, the Poisson process, is used in scenarios where we are counting the occurrences of events that appear at a certain rate. For example, we can use the Poisson process to model the number of car accidents at a given intersection, the number of photons that land on a photodiode, or the number of earthquakes that occur in a given region.

**For the following problem, let ![LaTeX: (N_t), t \geq 0](https://wustl.instructure.com/equation_images/(N_t)%252C%2520t%2520%255Cgeq%25200?scale=1 "(N_t), t \geq 0") be a Poisson process. Evaluate the given integral to compute ![LaTeX: P(N_s = 0, N_t = 1)](https://wustl.instructure.com/equation_images/P(N_s%2520%253D%25200%252C%2520N_t%2520%253D%25201)?scale=1 "P(N_s = 0, N_t = 1)") for any ![LaTeX: 0 \leq s \leq t](https://wustl.instructure.com/equation_images/0%2520%255Cleq%2520s%2520%255Cleq%2520t?scale=1 "0 \leq s \leq t").**

_Note, ![LaTeX: \lambda](https://wustl.instructure.com/equation_images/%255Clambda?scale=1 "\lambda") is the parameter for the Poisson distribution and represents the mean number of events within a given interval of time or space. It can be treated as a constant for the purposes of the integral._

![LaTeX: \begin{align*}
dN_{01}(x,y; \lambda) &= \lambda^2 e^{-\lambda(x+y)} \; dx \; dy \\
\implies P(N_s=0, N_t=1) &= \int_{s}^{t}\int_{t-x}^{\infty} \lambda^2 e^{-\lambda (x+y)} \; dy 
\; dx
\end{align*}](https://wustl.instructure.com/equation_images/%255Cbegin%257Balign*%257D%250AdN_%257B01%257D(x%252Cy%253B%2520%255Clambda)%2520%2526%253D%2520%255Clambda%255E2%2520e%255E%257B-%255Clambda(x%252By)%257D%2520%255C%253B%2520dx%2520%255C%253B%2520dy%2520%255C%255C%250A%255Cimplies%2520P(N_s%253D0%252C%2520N_t%253D1)%2520%2526%253D%2520%255Cint_%257Bs%257D%255E%257Bt%257D%255Cint_%257Bt-x%257D%255E%257B%255Cinfty%257D%2520%255Clambda%255E2%2520e%255E%257B-%255Clambda%2520(x%252By)%257D%2520%255C%253B%2520dy%2520%250A%255C%253B%2520dx%250A%255Cend%257Balign*%257D?scale=1 "\begin{align*}
dN_{01}(x,y; \lambda) &= \lambda^2 e^{-\lambda(x+y)} \; dx \; dy \\
\implies P(N_s=0, N_t=1) &= \int_{s}^{t}\int_{t-x}^{\infty} \lambda^2 e^{-\lambda (x+y)} \; dy 
\; dx
\end{align*}")