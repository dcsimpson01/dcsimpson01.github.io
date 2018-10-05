---
layout: post
title: "David Simpson, First Post"
date: 2018-10-04
---

This is a first test post. I plan to use this blog to post about topics that I am studying in political science. The page is powered by [Jekyll](http://jekyllrb.com) and I use Markdown to author my posts.

Test writing with latex: $\int_{x}^1f(x)dx$ for inline test.
Test2: writing with latex: \(\int_{x}^1f(x)dx\) for inline test.

And centered text writing:

$$y =3x+4$$

Test 2:
\[y =3x+4\]


Did it work?

 {% raw %}
  $$a^2 + b^2 = c^2$$ --> note that all equations between these tags will not need escaping! 
 {% endraw %}

Website for help:
https://stackoverflow.com/questions/26275645/how-to-support-latex-in-github-pages

Test again:
test 1 [](raw: 3x^2)
test 2 []($raw: 3x^2$)
test 3 []($$raw: 3x^2$$)

test 4 [](raw: \int_x^1 3x^2)
test 5 []($raw: \int_x^1 3x^2$)
test 6 []($$raw: \int_x^1 3x^2$$)
One more time and again.



More testing
$$
\begin{displaymath}
\int_x^1 3f(x)dx
\end{displaymath}
$$
More
$$
\begin{align*}
  & \phi(x,y) = \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right)
  = \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j) = \\
  & (x_1, \ldots, x_n) \left( \begin{array}{ccc}
      \phi(e_1, e_1) & \cdots & \phi(e_1, e_n) \\
      \vdots & \ddots & \vdots \\
      \phi(e_n, e_1) & \cdots & \phi(e_n, e_n)
    \end{array} \right)
  \left( \begin{array}{c}
      y_1 \\
      \vdots \\
      y_n
    \end{array} \right)
\end{align*}
$$

The following is a math block:

$$ 5 + 5 $$

But next comes a paragraph with an inline math statement:

\$$ 5 + 5 $$
