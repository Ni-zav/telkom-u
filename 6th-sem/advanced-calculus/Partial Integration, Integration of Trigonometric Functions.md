#adv-calculus #math

# partial integration
partial integration is boils down to: an integral function that is a multiplication of multiple integral functions. 
it has distinct characteristics: one function is not a derivative of another.
$$ \int u dv = uv - \int v du $$
the one for u is the one function that is simpler.

example:
1. calculate $\int x e^2 dx$!
		if $u = x$ , then $du = dx$.
		$dv = e^x dx \rightarrow v = \int e^x dx = e^x$
	therefore $\int x e^x dx = x e^x - \int e^x dx$
	$= x e^x - e^x + C$

partial integration can be done multiple time (more than one).

example:
2. calculate $\int x^2 \sin x dx$
	$= -x^2 \cos x + 2 \int x \cos x dx$
		if (i) $u = x^2 \rightarrow du = 2xdx$ and $dv = \sin xdx \rightarrow v = - \cos x$ 
	continue this

partial integration have integran $f(x)$, and can shows up multiple time.

example:
3. calculate $\int e^x \cos xdx$
		if $u = e^x \rightarrow du = e^x dx$
		$dv = \cos x dx \rightarrow v = \int \cos xdx = \sin x$
	therefore: $e^x \sin x - \int \sin x e^x dx$
	then you can do partial integration again
		if $u = e^x \rightarrow du = e^x dx$
		$dv = \sin x dx \rightarrow v = \int \sin xdx = - \cos x$
	therefore: $e^x \sin x - (e^x (-\cos x) - \int (-\cos x) e^x dx)$
	$\int e^x \cos xdx =e^x \sin x +e^x \cos x - \int e^x  \cos x dx + C$
	$2\int e^x \cos xdx  =e^x \sin x +e^x \cos x  + C$ (move the right integral to the left)
	$\int e^x \cos xdx = \frac{e^x \sin x +e^x \cos x}{2}+ C$

# trigonometric integration

Shape: $\int \cos ^n xdx$ and $\int \sin ^n xdx$

For n odd: $\sin ^n x = \sin x \sin ^{n-1} x$ and $\cos ^n x = \cos x \cos^{n-1}x$
	use identity $\sin ^2 x + \cos ^2 x = 1$

for n even: $\cos 2x = 2 \cos ^2x-1=1-2 \sin ^2x$ 
	use identity $sin ^nx= \sin ^{n-2}x$ and $\cos

