---
layout: post
title: Rendering LaTeX in Javascript with KaTeX and Jekyll
categories: latex
---
{% include katex_import.html %} 
I followed [this blog][xuchen-blog] to integrate latex in to this blog!

$$ \displaystyle P(x)=\frac{1}{\sigma\sqrt{2\pi}}e^{-\frac{(x-\mu)^2}{2\sigma ^2}} $$

[xuchen-blog]: https://xuc.me/blog/KaTeX-and-Jekyll/

{% include katex_render.html %} 