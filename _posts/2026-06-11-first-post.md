---
layout: post
title: "Change of basis"
---

\textbf{Change of coordinates}
Change of coordinates makes the most sense through the following diagram 


\[\begin{tikzcd}
	& V &&&&& W \\
	\\
	V &&&&& W \\
	\\
	& {\mathbb{F^n}} &&&&& {\mathbb{F^m}} \\
	\\
	{\mathbb{F^n}} &&&&& {\mathbb{F^m}}
	\arrow["T", from=1-2, to=1-7]
	\arrow["{\phi_{\beta'}}"{pos=0.4}, from=1-2, to=5-2]
	\arrow["{\phi_{\gamma'}}"'{pos=0.4}, from=1-7, to=5-7]
	\arrow["{I_V}", tail reversed, from=3-1, to=1-2]
	\arrow["T", from=3-1, to=3-6]
	\arrow["{\phi_\beta}"'{pos=0.4}, tail reversed, from=3-1, to=7-1]
	\arrow["{I_W}", tail reversed, from=3-6, to=1-7]
	\arrow["{\phi_\gamma}"'{pos=0.4}, tail reversed, from=3-6, to=7-6]
	\arrow["{[T]_{\beta'}^{\gamma'}}", from=5-2, to=5-7]
	\arrow["{Q = [I_V]_\beta^{\beta'}}"', tail reversed, from=7-1, to=5-2]
	\arrow["{[T]_\beta^\gamma}"', from=7-1, to=7-6]
	\arrow["{Q = [I_W]_\gamma^{\gamma'}}"', tail reversed, from=7-6, to=5-7]
\end{tikzcd}\]

The change of coordinate matrices Q,P are simply the matrix representations of the identity maps
$I_V:V \to V$ and $I_W: W \to W$ respectively. 
It is then clear what the formula $[T]_\beta^\gamma = Q[T]_{\beta'}^{\gamma'} P^{-1}$ is saying.
We are just saying that the bottom square commutes, of course, this is by definition of matrix multiplication
which was defined so that any square like this will commute! 
