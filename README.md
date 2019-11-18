# CobordismCube
Computes the cobordism cube homology of alternating links. (under development)

Given a knot diagram with n crossings, the n-dimensional cube obtained by switching the crossings (0 -> same crossings, 
1 -> swtiched crossing), and computing the Khovanov homology of these diagrams
defines a chain complex where the differentials are the maps (up to sign) on the Khovanov homology induced from the
link cobordisms that switches crossings.

The command CCKerImg picks up concrete representatives of the homology groups.
