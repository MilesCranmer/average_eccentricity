# Circularization Radius
Simple Monte Carlo estimate for the average radius where a binary becomes circular.

Monte Carlo -> Symbolic Regression produces the following results.

For a binary system with initial separation a0 and eccentricity e0, circularization is reached at afinal, which is approximated by:

Best fit:

afinal = 0.088*a0 + 0.034*a0*e0^2 + 0.017*a0/(0.012 + e0) - 0.14*a0*e0

Most elegant fit:

afinal = a0/(1 + 34 * e0)
