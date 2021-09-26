---
layout: page
title: Analysis of Crowd-generated code
description: 
img: /assets/img/code-snippet.jpg
---

During my PhD, I also worked on the analysis of online code snippets found in developers' forums, such as www.stackoverflow.com. Over time, StackOverflow  has collected millions of high-quality code snippets, which provide valuable resources for code reuse.  Recent surveys reported that developers search for code snippets in StackOverflow frequently and extensively.


However, there is a major obstacle in reusing such code snippets. The majority of code snippets in  StackOverflow do not compile indicating that manual effort is required to make them compilable. To reduce such manual effort, I developed CSnippex, the first technique that automatically turns code snippets found in StackOverflow into compilable code. I publicly released the tool and the compilable code snippets http://sccpu2.cse.ust.hk/csnippex/index.html obtained by analyzing 491,906 StackOverflow pages.

Currently, I am working on how to make such code snippets reusable.

Related publications: {% cite terragni-ase-2021 terragni-issta-2016 %}

{% bibliography --cited %}