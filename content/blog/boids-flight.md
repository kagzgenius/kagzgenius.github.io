---
external: false
title: "Boids: simulating flocks in go"
description: "Boids is an artificial life program, developed by Craig Reynolds in 1986, which simulates the flocking behaviour of birds. In this post, we will learn how to implement boids in Go."
date: 2024-06-24
---
## First things first: What are Boids? (Work in progress)

Developed by Craig Reynolds in 1986, boids is an artificial life program that simulates the flocking behaviour of birds. The program runs in O(n<sup>2</sup>) time complexity and has both 2-dimensional and 3-dimensional variants. In this post, we will learn how to implement boids in 2 dimensions using go and the graphics package (ebiten)[https://pkg.go.dev/github.com/hajimehoshi/ebiten/v2]

![2D boids simple](../../../main/src/img/go-boids.gif)

## References

Reynolds, Craig W. “Flocks, Herds and Schools: A Distributed Behavioral Model.” ACM SIGGRAPH Computer Graphics, vol. 21, no. 4, Aug. 1987, pp. 25–34. ACM Digital Library, https://doi.org/10.1145/37402.37406.

Boids (Flocks, Herds, and Schools: A Distributed Behavioral Model). http://www.red3d.com/cwr/boids/. Accessed 12 April 2024.

Parker, Conrad. Conrad Parker. https://vergenet.net/~conrad/boids/pseudocode.html#ref2. Accessed 12 April 2024.

