# Title

Benford's Law

# Metadata

## Type

Fun fact

# Main Version

## Statement

When you look at numbers found in real-world data sets, for most sets of numbers the first digit is more often a 1 than any other digit. 2 is a more common first digit than 3, and so on up to 9. In fact, the first digits often follow the same pattern (distribution).

![](Benford_s%20Law_images/image_0.png)

## Hint

Have a look at some data sets that span many orders of magnitude. For example, what are the first digits of: the first 100 prime numbers (or more!), the populations of the countries in Africa, the heights of the tallest buildings in the world?

## Explanation

Many data sets (for example, populations of countries, heights of buildings, stock prices) or famous sequences (Fibonacci numbers, prime numbers) are spread over very different scales (orders of magnitude). Many of these big sets of data arise from decreasing power laws. A simple example might be  </p>\n<p>y = k\u00d710\u207d\u207b\u1d43\u02e3\u207e where k, a &gt; 0. Choosing a = 0.1 and k = 1000 gives the following:</p>\n<p><img alt=\"\" src=\"assets/images/Benford_s_Law_image_1.png\" class=\"Benford_s_Law_image_1\" /></p>\n<p>Power laws will look like a straight line on semi-log graph paper - where the y-axis is on a log-scale paper. We can show this by rewriting our formula for the power law y = k\u00d710\u207d\u207b\u1d43\u02e3\u207e = 10\u1d47\u00d710\u207d\u207b\u1d43\u02e3\u207e = 10\u207d\u207b\u1d43\u02e3\u207a\u1d47\u207e , and then applying a logarithm on both sides: log\u2081\u2080(y) = - a\u00d7x + b. This is the equation when the y-axis is on a log scale. The same example is shown below:</p>\n<p><img alt=\"\" src=\"assets/images/Benford_s_Law_image_2.png\" class=\"Benford_s_Law_image_2\" /></p>\n<p>The horizontal lines represent 1, 2, 3, 4, \u2026, 10, 20, 30, \u2026, 100, 200, 300, \u2026 and note they are unevenly spaced on the y axis! The largest spaces are between 1 and 2, between 10 and 20, and between 100 and 200. The smallest spaces are between 9 and 10, 90 and 100.</p>\n<p>Try picking random values of x, and reading off corresponding values of y from our (power law) straight line. Because of the spacing of the horizontal lines we see that we are most likely to get a value of y with first digit 1, then we are next likely to get a value of y with a first digit 2, etc. These probabilities are what leads to Benford's Law.  

y = k×10⁽⁻ᵃˣ⁾ where k, a > 0. Choosing a = 0.1 and k = 1000 gives the following:

![](Benford_s%20Law_images/image_1.png)

Power laws will look like a straight line on semi-log graph paper - where the y-axis is on a log-scale paper. We can show this by rewriting our formula for the power law y = k×10⁽⁻ᵃˣ⁾ = 10ᵇ×10⁽⁻ᵃˣ⁾ = 10⁽⁻ᵃˣ⁺ᵇ⁾ , and then applying a logarithm on both sides: log₁₀(y) = - a×x + b. This is the equation when the y-axis is on a log scale. The same example is shown below:

![](Benford_s%20Law_images/image_2.png)

The horizontal lines represent 1, 2, 3, 4, …, 10, 20, 30, …, 100, 200, 300, … and note they are unevenly spaced on the y axis! The largest spaces are between 1 and 2, between 10 and 20, and between 100 and 200. The smallest spaces are between 9 and 10, 90 and 100.

Try picking random values of x, and reading off corresponding values of y from our (power law) straight line. Because of the spacing of the horizontal lines we see that we are most likely to get a value of y with first digit 1, then we are next likely to get a value of y with a first digit 2, etc. These probabilities are what leads to Benford's Law. 

# Extension 1

## Statement

Can you think of which sets of numbers do not obey Benford's law?

## Hint

The explanation of Benford's law mentioned that the data set typically spans many orders of magnitude.

## Explanation

Anything that is within a small range, an example would be something normally distributed E.g Measure everyone's height (in metres). Almost all heights would begin with a 1.

# Additional information

## About

Benford's Law is used in the real world to check for fraud on big data sets. If they don't follow the law when they should, it is possible they have been falsified!

## References

* https://brilliant.org/wiki/benfords-law/

* https://towardsdatascience.com/what-is-benfords-law-and-why-is-it-important-for-data-science-312cb8b61048

