# Major League Baseball Player Analysis
Our project type is an application flavor project. The dataset is from Fangraphs.com and is of the 2024 MLB (Major League Baseball) position player statistics. The dataset contains just the players who were qualified batters that season (need 502 or more plate appearances to be deemed qualified). There are 129 observations (players) and 23 variables. The problem our project will address is to determine if there are any statistical differences in some of the main baseball statistical categories for the different positions. The goal is to explore these differences and try to quantify which position groups did better or worse for the variables of interest. It is believed by fans that some positions are more focused on defense, some are more focused on batting average, some are more focused on batting power, and etc. The purpose of this project is to test to see if there are differences using some of the statistics from the 2024 season. 
The project is split into three main analyses: MAVONA with position as the categorical variable (4 categories) and with HR (home runs), Avg (batting average), WAR (wins above replacement), and RBI (runs batted in) as the variables being tested for differences; another MAVONA with position as the categorical variable (4 categories) and with Def (total defensive rating), BB/K (walk to strikeout ratio), Spd (total speed rating), and BABIP (batting average on balls in play) as the variables being tested for differences; and a cluster analysis for these 8 quantitative variables to further explain any relationships between them.
Python is the software that will be used. The only other resource that is necessary is the dataset from Fangraphs as an excel file.

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
