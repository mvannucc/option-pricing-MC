# Option Pricing using Monte Carlo Simulation

Implementation of European & binary option pricing under the risk-neutral measure via Monte Carlo.  
Simulated the underlying asset with three discretization schemes (Euler–Maruyama, Milstein, Closed-form).  
Compared the resulting option prices with each other and with the Black–Scholes closed-form solution,  
and studied sensitivity to simulation parameters.

## Repo Contents
- `option_pricing_MC.ipynb` – code implementation (no outputs).
- `Outputs/` – key plots from simulations.

## Example Result
![Convergence of MC price](Outputs/sensitivity/nsim/nsim_european.png)

## References

- Jäckel, P. (2002) - Monte Carlo Methods in Finance
- https://hautahi.com/sde_simulation
