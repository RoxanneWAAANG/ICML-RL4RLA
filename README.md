# ICML-RL4RLA

![img1](fig/eigenvalue_convergence.png)

***Figure 1:** Rayleigh quotient ρ(x_t) over iterations for algorithms discovered by RL4RLA on the symmetric PSD eigenvalue problem. C0 and C1 rediscover exact power iteration on small (n=5) and medium (n=50) systems, converging to the true λ_max=1. C2 rediscovers sketched power iteration on a large system (n=500), converging to ρ≈0.87 — the expected asymptote for a sketched variant trading accuracy for computational efficiency. All results are consistent across 5 independent seeds.*


![img2](fig/all_systems_runtime_vs_residual.svg)

***Figure 2:** Runtime vs. residual comparison between RL4RLA-discovered algorithms and AlgoTune across 5 system families (3×3 grid, each subplot representing one system configuration). RL4RLA methods (Full Newton, Newton Sketch) consistently achieve residuals below $10^{-11}$. AlgoTune variants (Mid Low, Mid High, Logistic) achieve faster runtimes in some regimes, notably by invoking optimized library solvers in the logistic setting, but at significantly higher residuals under ill-conditioning and high leverage variance. This illustrates that implementation-level optimization cannot compensate for structural algorithmic limitations.*
