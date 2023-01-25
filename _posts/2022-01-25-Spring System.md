---
title: "Simulating Fabrics: A Spring Element Approach"
date: 2023-01-25
---
# Introduction
In the era of deep learning and data-driven approaches to computer vision, there's a certain beauty to classical computer vision techniques. This post is about one such idea.

Recently, as part of some work, I'd been exploring the idea of warping pixels in 2D images using 3D mesh information. As a part of this, I investigated using spring elements, a technique from finite element (FEM) analysis, to come up with a fast efficient solution. This technique is also used in computer graphics to simulate the movement of frabrics in 2D.

Hence, I'll be 

# Spring Elements?
To begin with, let's go over how we'll implement the system. We'll start with defining some convenient groupings for points in the image to move.
$$\sum_{n=1}^\infty 1/n^2 = \frac{\pi^2}{6}$$
