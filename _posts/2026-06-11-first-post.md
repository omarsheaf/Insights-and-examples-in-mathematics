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

The change-of-coordinate matrices $Q$ and $P$ are simply the matrix representations of the identity maps

$$
I_V : V \to V
$$

and

$$
I_W : W \to W
$$

respectively.

If

$$
Q = [I_V]_{\beta}^{\beta'}
$$

and

$$
P = [I_W]_{\gamma}^{\gamma'},
$$

then

$$
[T]_{\beta}^{\gamma}
=
P^{-1}[T]_{\beta'}^{\gamma'}Q.
$$