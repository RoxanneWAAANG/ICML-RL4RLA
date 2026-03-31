![img1](fig/eigenvalue_convergence.png)

***Figure 1:** Rayleigh quotient ρ(xₜ) over iterations for algorithms discovered by RL4RLA on the symmetric PSD eigenvalue problem (higher is better; ρ=1 indicates exact recovery of λₘₐₓ). C0 and C1 show power iteration on systems of size n=5 and n=50. C2 shows sketched power iteration on n=500. Results averaged over 5 independent seeds.*

![img2](fig/logistic.svg)

***Figure 2:** Runtime (ms) vs. residual for RL4RLA-discovered methods (Full Newton, Newton Sketch) and AlgoTune on the logistic regression system.*

![img3](fig/msd.png)

***Figure 3:** Runtime vs. final relative residual on YearPredictionMSD. Each point corresponds to one of 30 independent runs.*

![img4](fig/all_systems_runtime_vs_residual.svg)

***Figure 4:** Runtime vs. residual for RL4RLA-discovered methods (Full Newton, Newton Sketch) and AlgoTune variants (Mid Low, Mid High, Logistic) across 5 system families. Each subplot represents one system configuration.*
