---
layout: post
title: "Your Post Title"
nav_exclude: true
katex: true
---

{% if page.katex %}

<!-- CSS -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@latest/dist/katex.min.css"/>

<!-- JavaScript -->
<script defer src="https://cdn.jsdelivr.net/npm/katex@latest/dist/katex.min.js"></script>
<script defer src="https://cdn.jsdelivr.net/npm/katex@latest/dist/contrib/auto-render.min.js"
  onload="renderMathInElement(document.body,{
    delimiters: [
      { left: '$$',  right: '$$',  display: true  },
      { left: '$',   right: '$',   display: false },
      { left: '\\[', right: '\\]', display: true  },
      { left: '\\(', right: '\\)', display: false }
  ]});">

{% endif %}

This is an example of inline \\(\LaTeX\\). The following is Stokes' theorem in a
`displaymath` environment: \$$\int_{\partial \Omega} \omega = \int_{\Omega} d\omega\$$
