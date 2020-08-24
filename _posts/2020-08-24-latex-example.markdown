---
layout: post
title:  "LaTeX examples"
date:   2020-08-24 10:40:04 +0200
categories: jekyll update
---

Inline: {% katex %}
c = \pm\sqrt{a^2 + b^2}
{% endkatex %}

block:
{% katex display %}
c = \pm\sqrt{a^2 + b^2}
{% endkatex %}

math mode:
{% katexmm %}
This is a mixed environment where you can have normal text and inline latex $\lVert x \rVert $, \$1! and block latex $$\sqrt{x+y}$$ 
{% endkatexmm %}