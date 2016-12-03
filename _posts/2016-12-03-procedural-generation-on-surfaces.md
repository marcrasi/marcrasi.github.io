---
layout: post
title: "Procedural Generation on Surfaces"
date: 2016-12-03 14:00:00 -0800
categories: procedural-generation
---

I want to procedurally generate a pretty map to print on a tshirt with all-over tshirt printing. I want the procedural generation to be aware of the geometry and topology of the tshirt so that it can create things like roads and rivers that actually wrap around it in the right places.

To start, I'm going to implement [Straightest Geodesics on Polyhedral Surfaces][geodesics] to make it easy for me to run simulations and stuff on a t-shirt-shaped surface. The authors of that paper made a [cool video][cool-video].

This implementation will be happening [here][github-procedural-generation].

[geodesics]: http://geometry.caltech.edu/pubs/GSD06.pdf
[cool-video]: https://www.youtube.com/watch?v=bX_dsbiDfZw
[github-procedural-generation]: https://github.com/marcrasi/side-projects/tree/master/procedural-generation
