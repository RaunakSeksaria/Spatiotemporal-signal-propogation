## Reproducing the Results of Paper [Spatiotemporal Signal Propagation in Complex Networks, C. Hens](https://par.nsf.gov/servlets/purl/10111417)

### Objectives:
- Study signal propagation on various kinds of graphs, including:
  - **Erdős–Rényi Graphs**
  - **Barabási–Albert Graphs**
  - Other network types
- Analyze different models, including:
  - **SIS Model** for disease propagation
  - **Michaelis–Menten Model** for kinetics

### Approach:
1. Implement and simulate network models to generate graph structures.
2. Simulate signal propagation dynamics using the specified models.
3. Evaluate spatiotemporal patterns and compare them with the results from the paper.
4. Study the effect of varying parameters (e.g., infection rates, reaction constants) on signal propagation.

### Tools & Libraries:
- Python libraries: **NetworkX**, **NumPy**, **SciPy**, **Matplotlib**, etc.
- For performance optimization: Consider **Numba** or **Cython**.
- Visualization: Use **Seaborn** for heatmaps and propagation patterns.
