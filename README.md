# Derivative-Pricing-Toolkit

Python implementations of financial derivative pricing methods and numerical risk tools.

This repository includes:

1. Option pricing models for:

   * European options (Closed-form Black-Scholes-Merton);
   * European options (Monte Carlo simulation);
   * European options (Binomial Tree method);
   * American options (Binomial Tree method).

All current implementations utilize standard Python libraries (NumPy, SciPy) for vectorized numerical calculations.

2. Planned additions (Currently in development):

   * Exotic option pricing (Asian, Barrier, Binary, and Basket options);
   * Variance reduction techniques for Monte Carlo (Antithetic variates, Control variates);
   * Risk sensitivities (Greeks: Delta, Gamma, Theta, Vega, Rho);
   * Greek extraction directly from Binomial Trees and via Monte Carlo bump-and-revalue.