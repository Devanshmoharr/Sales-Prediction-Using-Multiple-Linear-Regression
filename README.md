**Sales-Prediction-Using-Multiple-Linear-Regression**

Python, Scikit-Learn, Pandas, Seaborn, Matplotlib, Yellowbrick

Developed a series of predictive models to forecast sales based on advertising spend across TV, Radio, and Newspaper channels. Instead of settling for a single model, I built and compared three distinct regression approaches to find the optimal solution.

🔹 Model Iteration & Comparison:

Baseline Model: Built a simple regression using TV and Radio spend. Achieved an R² of 0.897.
Full Feature Model: Added Newspaper spend to test its impact. The R² remained similar (~0.897), indicating Newspaper had negligible influence on sales.
Interaction Model (The Winner): Engineered a new feature (TV × Radio) to capture the synergistic effect of combined ad spending. This model achieved an outstanding R² of 0.979 and reduced RMSE to 0.701.

🔹 Key Insights:

Identified that TV and Radio are the primary drivers of sales.
Discovered a strong interaction effect: spending on both channels simultaneously yields higher returns than the sum of individual spends.
Validated findings using correlation heatmaps and residual analysis.

🔹 Tech Stack: Python, Scikit-Learn, Pandas, Seaborn, Yellowbrick, Matplotlib.

🎬 Watch the Project Walkthrough: https://www.youtube.com/watch?v=qdyWyvhBNfs
