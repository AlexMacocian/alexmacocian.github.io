---
layout: post
title: "Implementing blur effect"
date: 2019-03-24
---

As part of the Monomenu framework I've been working on recently, I've decided to a base for effects as well as one implementation as proof of concept.

I've decided to implement the blur effect as it is pretty well documented and the implementation is not that complicated.

Taking inspiration from WPF, I've decided to implement blurring using a Gaussian function. By playing with the kernel of the Gaussian, I could achieve both a Gaussian blur (https://en.wikipedia.org/wiki/Gaussian_blur) as well as a box blur (https://en.wikipedia.org/wiki/Box_blur).


Initially, to keep all the code done in C# and CPU bound, I wrote the function that b
