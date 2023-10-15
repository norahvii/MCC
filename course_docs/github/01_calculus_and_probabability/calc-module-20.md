Calc Module 20: Integral Change of Coordinates and Transformations of Random Variables
--------------------------------------------------------------------------------------

![Calculus Banner.svg](https://wustl-catalog.instructure.com/courses/254/files/25266/download)

### Topics Covered

*   Integral Change of Coordinates
*   Transformations of Random Variables

14.2 Change to Better Coordinates
---------------------------------

✅  **Task:** Read Chapter 14.2 (pg. 527-534). Complete the following **exercises: 15, 19, 22, 23** (pg. 334) and compare your work to the solutions (where possible).

💡 **Tip**: If you get stuck on a concept or problem, ask a tutor or refer to the solution for a hint. Don’t spend too long getting hung up on one point!

Transformations of Random Variables
-----------------------------------

✅  **Task:** Complete the exercises below. You may find it helpful to refer to Chapter 8.4 and Chapters 14.1-14.3 of Strang.

### Exercise

1\. Show that

![LaTeX: \frac{1}{\sigma\sqrt{2\pi}} \int_{-\infty}^{\infty} e^{-x^2/2\sigma^2} dx = \frac{1}{\sqrt{\pi}} \int_{-\infty}^{\infty} e^{-u^2} du = 1](https://wustl.instructure.com/equation_images/%255Cfrac%257B1%257D%257B%255Csigma%255Csqrt%257B2%255Cpi%257D%257D%2520%255Cint_%257B-%255Cinfty%257D%255E%257B%255Cinfty%257D%2520e%255E%257B-x%255E2%252F2%255Csigma%255E2%257D%2520dx%2520%253D%2520%255Cfrac%257B1%257D%257B%255Csqrt%257B%255Cpi%257D%257D%2520%255Cint_%257B-%255Cinfty%257D%255E%257B%255Cinfty%257D%2520e%255E%257B-u%255E2%257D%2520du%2520%253D%25201?scale=1 "\frac{1}{\sigma\sqrt{2\pi}} \int_{-\infty}^{\infty} e^{-x^2/2\sigma^2} dx = \frac{1}{\sqrt{\pi}} \int_{-\infty}^{\infty} e^{-u^2} du = 1")

_Hint_: Define the integral ![LaTeX: I=\int_{-\infty}^\infty e^{-x^2} \; dx](https://wustl.instructure.com/equation_images/I%253D%255Cint_%257B-%255Cinfty%257D%255E%255Cinfty%2520e%255E%257B-x%255E2%257D%2520%255C%253B%2520dx?scale=1 "I=\int_{-\infty}^\infty e^{-x^2} \; dx") and write an expression for ![LaTeX: I^2](https://wustl.instructure.com/equation_images/I%255E2?scale=1 "I^2") with two different dummy variables; use the coordinate transformation ![LaTeX: (x,y) \to (r,\theta)](https://wustl.instructure.com/equation_images/(x%252Cy)%2520%255Cto%2520(r%252C%255Ctheta)?scale=1 "(x,y) \to (r,\theta)") to evaluate your expression for ![LaTeX: I^2](https://wustl.instructure.com/equation_images/I%255E2?scale=1 "I^2").

2\. Suppose ![LaTeX: X \sim N(0,1)](https://wustl.instructure.com/equation_images/X%2520%255Csim%2520N(0%252C1)?scale=1 "X \sim N(0,1)") is a stanard normal variable (i.e., ![LaTeX: f_X(x) = \frac{1}{\sqrt{2\pi}} e^{-x^2/2}](https://wustl.instructure.com/equation_images/f_X(x)%2520%253D%2520%255Cfrac%257B1%257D%257B%255Csqrt%257B2%255Cpi%257D%257D%2520e%255E%257B-x%255E2%252F2%257D?scale=1 "f_X(x) = \frac{1}{\sqrt{2\pi}} e^{-x^2/2}")) and define a new random variable ![LaTeX: Y = aX + b](https://wustl.instructure.com/equation_images/Y%2520%253D%2520aX%2520%252B%2520b?scale=1 "Y = aX + b"). Compute ![LaTeX: f_Y](https://wustl.instructure.com/equation_images/f_Y?scale=1 "f_Y") by computing ![LaTeX: F_Y](https://wustl.instructure.com/equation_images/F_Y?scale=1 "F_Y") in terms of ![LaTeX: F_X](https://wustl.instructure.com/equation_images/F_X?scale=1 "F_X") and differentating.

1.  1.  What type of distribution does the new random variable ![LaTeX: Y](https://wustl.instructure.com/equation_images/Y?scale=1 "Y") have?
    2.  What are the mean and variance of ![LaTeX: f_Y](https://wustl.instructure.com/equation_images/f_Y?scale=1 "f_Y")?
    3.  How does your result relate to problem 14.2.23 from Strang’s text?
    4.  What do implications do your findings have for the importance of satisfying normality assumptions when using general linear models (GLMs)? If you’re unsure, try repeating the above steps with ![LaTeX: f_X(x) = \lambda e^{-\lambda x}](https://wustl.instructure.com/equation_images/f_X(x)%2520%253D%2520%255Clambda%2520e%255E%257B-%255Clambda%2520x%257D?scale=1 "f_X(x) = \lambda e^{-\lambda x}") and seeing how your results differ.

🎉Congrats on finishing the Calculus Crash Course! If you want to receive feedback on any problems, make sure to submit them [here](https://wustl-catalog.instructure.com/courses/254/discussion_topics/722 "[Calc] Discussion: Techniques and Applications of Integration"). **In addition, t****ake the final quiz to test your knowledge.**