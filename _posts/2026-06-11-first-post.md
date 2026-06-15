---
layout: post
title: "Change of Coordinates"
---

## Change of coordinates

Change of coordinates makes the most sense through the following diagram.

<figure class="figure">
  <img
    src="{{ '/assets/images/change-of-coordinates/diagram.png' | relative_url }}"
    alt="Change of coordinates diagram"
    class="diagram"
  >
  <figcaption class="caption">
    The coordinate diagrams for a linear map under two choices of bases.
  </figcaption>
</figure>

The change-of-coordinate matrices $Q$ and $P$ are simply the matrix representations of the identity maps and this diagram commutes as seen in my previous post by definition of matrix multiplication. What we wanted was multiplication defined such that the matrix representation of the composition of linear maps is the multiplication of the matrices. So what the formula

$$[T]_\beta^\gamma = P^{-1} [T]_{\beta'}^{\gamma'} Q$$
says is just that again, that $[T]_\beta^\gamma$ is the same as taking the other path along this square. 