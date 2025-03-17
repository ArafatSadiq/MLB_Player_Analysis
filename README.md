# MLB_Player_Analysis
🏆 MLB Player Performance Analysis
Exploring Position-Based Differences in Player Metrics

This project analyzes MLB player statistics to determine how position groups (CI, MI, OF) impact key performance metrics.
I contributed to the MANOVA analysis, checking assumptions, performing ANOVA, and conducting post-hoc tests.
Where (CI- Corner Infielders), (MI- Middle Infielders), (OF- OutFielders)

📊 Key Analyses in This Repository
✔ Assumption Checks (Normality, Homogeneity of Variance)
✔ MANOVA (Multivariate Analysis of Variance) → Tests overall position-based effects
✔ ANOVA (Univariate Tests) → Identifies specific performance metrics that differ
✔ Tukey’s Post-Hoc Test → Determines which position groups differ
✔ Visualizations (Boxplots) → Compares distributions of Speed & Defense

📂 Files Included
mlb_manova_analysis.py → Python script for MANOVA & post-hoc tests
mlb_visualizations.py → Boxplot visualizations
README.md → Project documentation
📌 Key Findings
✔ Speed (Spd_sqrt) and Defense (Def) significantly differ across position groups.
✔ Corner Infielders (CI) are the fastest, while Middle Infielders (MI) have the lowest defense ratings.
✔ Outfielders (OF) and CI have similar defensive ability.

🛠 How to Run the Code
Install dependencies:
pip install pandas numpy scipy statsmodels seaborn matplotlib


📢 Acknowledgment
This is part of a group project, and I contributed to the statistical analysis and visualizations. The full project includes additional insights from my teammates.

📧 Contact
For questions, feel free to reach out via GitHub or LinkedIn.
