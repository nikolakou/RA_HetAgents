# RA_HetAgents

These are a selection of codes on heterogeneous agent models that I am working on with [Gianluca Violante](https://sites.google.com/a/princeton.edu/glviolante/). All of these codes are written in Julia. Some codes (such as the heterogeneous agent New Keynesian model that uses the sequence space jacobian) use python routines written by Adrien Auclert, Bence Bardóczy, Matthew Rognlie, and Ludwig Straub from their paper ["Using the Sequence-Space Jacobian to Solve and Estimate Heterogeneous-Agent Models"](https://scholar.harvard.edu/files/straub/files/sequence_space_jacobian.pdf).

These are the codes you can *currently* find in the repository:

1. "rowenhorst_tauchen.jl": functions that discretize univariate AR(1) processes
2. "income_process_simulations.ipynb": income process simulations using Rowenhorst and Tauchen
3. "EGM.ipynb": Carrol's (2006) endogenous gridpoint method without labor choice
4. "EGM.ipynb": Carrol's (2006) endogenous gridpoint method with separable labor in utility
5. "IFP_finite_horizon.ipynb": the income fluctuations problem with a finite horizon
6. "VFI_no_labor.ipynb": standard value function iteration with no labor + Howard improvement step
7. "VFI_with_labor.ipynb": standard value function iteration with labor + Howard improvement step
8. "collocation.ipynb": value function iteration using collocation methods with labor supply
9. "stationary_distributions.ipynb": obtaining stationary distributions in the income fluctuations problem using (i) simulation, (ii) Young's (2010) method, and (iii) the eigenvector method
10. "Aiyagari_no_labor.ipynb": solving for the general equilibrium steady-state of the Aiyagari model with no labor supply
12. "Aiyagari_with_labor.ipynb": solving for the general equilibrium steady-state of the Aiyagari model with labor supply choice
13. "Krussel_Smith_SSJ.ipynb": obtaining transitional dynamics in the Krussel-Smith model using the sequence-space Jacobian method
14. (a) "HANK.ipynb": the main file that (i) solves a HANK model, (ii) calibrates the steady-state, (iii) obtains transitional dynamics, and (iv) simulates an economy with aggregate shocks using the [BKM](https://ideas.repec.org/a/eee/dyncon/v89y2018icp68-92.html) (2018) method
(b) "HANK_supplement.ipynb": Python code that uses Auclert et al.'s (2021) code to find Jacobians of simple blocks, accumulate, and obtain the general equilibrium Jacobians.

