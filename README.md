# Vivek Raj Singh

I am a quantitative researcher and computational modeling engineer focused on the intersection of advanced mathematics and high-performance systems. My work involves designing and implementing stochastic differential equations, jump-diffusion processes, and Monte Carlo simulations for financial engineering, specifically in derivatives pricing, volatility surface modeling, and risk assessment (VaR).

I build deterministic numerical engines primarily using C++, Python, and Scilab, leveraging quantitative libraries like NumPy, Pandas, SciPy, and PyTorch. Currently, my research focuses on options pricing (Black-Scholes, Volatility Surfaces, Greeks), stochastic calculus (Itô's Lemma, Brownian Motion, Jump-Diffusion Models), risk management, and algorithmic trading microstructure.

## Selected Work

**[Variance-Gamma-Engine](https://github.com/vivekrajsingh04/variance-gamma-engine)**
Implemented the Variance Gamma option pricing model (Madan, Carr, Chang). This engine models asset returns as Brownian motion evaluated at a random time given by a gamma process, effectively capturing fat tails and skewness in financial returns. The implementation is validated against European option market prices.

**[Heston-SV-Engine](https://github.com/vivekrajsingh04/heston-sv-engine)**
A high-fidelity implementation of the Heston Stochastic Volatility Model. It features a dual-validation architecture that computes prices via Monte Carlo simulations (utilizing Antithetic Variates for variance reduction) and analytical numerical Fourier inversion. The system automatically extracts implied volatility smiles and 3D pricing surfaces.

**[Stochastic-Storage-VaR](https://github.com/vivekrajsingh04/stochastic-storage-var)**
A computational framework modeling stochastic volatility and Value at Risk (VaR) specifically for storage constraints in energy markets. It develops computational engines to evaluate risk under uncertainty using jump-diffusion characteristics.

---
*Writing robust code for complex markets.*
