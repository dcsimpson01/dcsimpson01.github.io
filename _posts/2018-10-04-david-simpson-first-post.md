---
layout: post
title: "Getting Started"
date: 2018-10-04
---
## What this is:
This is a first test post. The page is powered by [Jekyll](http://jekyllrb.com) and I will use Markdown, and ocassionally HTML to author my posts.

## Where it is going:
I plan to use this blog to post about topics that I am studying in political science. I am excited that I can use this website to easily write short responses, use LaTeX to write math equations, and post findings from my data science work in R.

## LaTeX comments:
I am using [kramdown](https://kramdown.gettalong.org/syntax.html#math-blocks), based on Markdown, to write in LaTeX. The below equation is an example pulled from the kramdown webpage:

\$$
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
