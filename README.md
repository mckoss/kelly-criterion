# The Kelly Criterion - "The Fundamental Theory of Investing"

This is an educational repo explaining the Kelly Criterion and related
investment concepts.

Excellent information on the Kelly Criterion can be found at:

- [Kelly Criterion on Wikipedia](https://en.wikipedia.org/wiki/Kelly_criterion)
- [Fortune's Formula](https://archive.org/details/fortunesformulau00poun/page/n3/mode/2up) - a book by William Poundstone.

*To read the formulas as they are meant to appear, please visit the
[Kelly-Criterion](http://mckoss.com/kelly-criterion/) hosted version
of this repository.*

# What is it?

This simple formula:

<div style="text-align: center; font-size: 2rem;">

$f = p - \frac{1-p}{b}$

</div>

answers an amazingly complex question:

> Given a change to place a bet, at a given odds (payoff for a win), and a given
> probability of winning; how much of my money (stake) should I put at risk
> each time I place a bet?

<script defer>
MathJax = {
  tex: {
    inlineMath: [['$', '$'], ['\\(', '\\)']]
  }
};
</script>

<script id="MathJax-script" defer
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js">
</script>
