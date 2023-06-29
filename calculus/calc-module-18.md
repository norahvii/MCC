Calc Module 18: Integration by Parts & Higher Moments of Distributions
----------------------------------------------------------------------

![Calculus Banner.svg](https://wustl-catalog.instructure.com/courses/254/files/25266/download)

### Topics Covered

*   Integration by Parts
*   The ![LaTeX: k^\text{th}](https://wustl.instructure.com/equation_images/k%255E%255Ctext%257Bth%257D?scale=1 "k^\text{th}") Moment of a Distribution

7.1 Integration by Parts
------------------------

✅  **Task:** Read Chapter 7.1 (pg. 283-287). Complete the **following exercises: 55, 56** (pg. 287-288) and compare your work to the solutions (where possible).

💡 **Tip**: If you get stuck on a concept or problem, ask a tutor or refer to the solution for a hint. Don’t spend too long getting hung up on one point!

Higher Moments of Distributions
-------------------------------

✅  **Task:** Complete the exercise below. You may find it helpful to reference Chapter 8.4 (pg. 328-334) of Strang.

### Exercise

Suppose a random variable ![LaTeX: X](https://wustl.instructure.com/equation_images/X?scale=1 "X") is distributed according to ![LaTeX: f_X(x) = \frac{1}{\sigma\sqrt{2\pi}} e^{-x^2/2\sigma}](https://wustl.instructure.com/equation_images/f_X(x)%2520%253D%2520%255Cfrac%257B1%257D%257B%255Csigma%255Csqrt%257B2%255Cpi%257D%257D%2520e%255E%257B-x%255E2%252F2%255Csigma%257D?scale=1 "f_X(x) = \frac{1}{\sigma\sqrt{2\pi}} e^{-x^2/2\sigma}"). The _**expectation value of the ![LaTeX: n^\text{th}](https://wustl.instructure.com/equation_images/n%255E%255Ctext%257Bth%257D?scale=1 "n^\text{th}") moment of ![LaTeX: X](https://wustl.instructure.com/equation_images/X?scale=1 "X")**_ , denoted ![LaTeX: E[X^n]](https://wustl.instructure.com/equation_images/E%255BX%255En%255D?scale=1 "E[X^n]"), is given by the following formula:

![LaTeX: E[X^n] = \int_{-\infty}^\infty x^n f_X(x) \; dx](https://wustl.instructure.com/equation_images/E%255BX%255En%255D%2520%253D%2520%255Cint_%257B-%255Cinfty%257D%255E%255Cinfty%2520x%255En%2520f_X(x)%2520%255C%253B%2520dx?scale=1 "E[X^n] = \int_{-\infty}^\infty x^n f_X(x) \; dx")

Compute ![LaTeX: E[X^{2k}]](https://wustl.instructure.com/equation_images/E%255BX%255E%257B2k%257D%255D?scale=1 "E[X^{2k}]") and ![LaTeX: E[X^{2k-1}]](https://wustl.instructure.com/equation_images/E%255BX%255E%257B2k-1%257D%255D?scale=1 "E[X^{2k-1}]") in terms of ![LaTeX: k](https://wustl.instructure.com/equation_images/k?scale=1 "k"), where ![LaTeX: k](https://wustl.instructure.com/equation_images/k?scale=1 "k") is an unspecified integer.

_**Hint**_: If you’d rather not try this directly, begin by computing ![LaTeX: E[X]](https://wustl.instructure.com/equation_images/E%255BX%255D?scale=1 "E[X]") and ![LaTeX: E[X^2]](https://wustl.instructure.com/equation_images/E%255BX%255E2%255D?scale=1 "E[X^2]"), and then try to use the formula given by exercise 56 from Chapter 7.1 of Strang (written below for reference).

After ![LaTeX: n](https://wustl.instructure.com/equation_images/n?scale=1 "n") integrations by parts, ![LaTeX: \int u(dv/dx)dx](https://wustl.instructure.com/equation_images/%255Cint%2520u(dv%252Fdx)dx?scale=1 "\int u(dv/dx)dx") becomes

![LaTeX: uv-u^{(1)}v_{(1)} + u^{(2)}v_{(2)} - \dots + (-1)^n \int u^{(n)} v_{(n-1)} dx](https://wustl.instructure.com/equation_images/uv-u%255E%257B(1)%257Dv_%257B(1)%257D%2520%252B%2520u%255E%257B(2)%257Dv_%257B(2)%257D%2520-%2520%255Cdots%2520%252B%2520(-1)%255En%2520%255Cint%2520u%255E%257B(n)%257D%2520v_%257B(n-1)%257D%2520dx?scale=1 "uv-u^{(1)}v_{(1)} + u^{(2)}v_{(2)} - \dots + (-1)^n \int u^{(n)} v_{(n-1)} dx")

 ![LaTeX: u^{(n)}](https://wustl.instructure.com/equation_images/u%255E%257B(n)%257D?scale=1 "u^{(n)}") is the nth derivative of ![LaTeX: u](https://wustl.instructure.com/equation_images/u?scale=1 "u") and ![LaTeX: v_{(n)}](https://wustl.instructure.com/equation_images/v_%257B(n)%257D?scale=1 "v_{(n)}") is the nth integral of ![LaTeX: v](https://wustl.instructure.com/equation_images/v?scale=1 "v").