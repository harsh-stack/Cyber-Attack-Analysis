Cyber Attack Financial Analysis (2015-2024)
[
[
[

Analysis of 3,001 global cybersecurity incidents from Kaggle data, focusing on financial losses (~50M USD mean/year), attack patterns, and predictive modeling. Created for UMass Dartmouth BADM Final Project.

📊 Key Insights
Loss Trends: Mean losses stable ~50M USD; peak 2021, low 2018.
​

Top Attacks: DDoS (17.7%), Phishing (17.6%), Ransomware (16.4%).
​

XGBoost Model: Predicts losses (max_depth=6, eta=0.3); top features: affected users, resolution time.
​

Sectors Hit Hardest: Government/IT highest avg losses (~52M USD).
​

Defenses: VPN/Antivirus most common; heatmap shows gaps (e.g., DDoS vs. AI Detection).
​

🛠️ Quick Start
Install deps:

r
install.packages(c("dplyr", "ggplot2", "corrplot", "xgboost", "readr"))
Run analysis:

r
rmarkdown::render("final.Rmd")
Key outputs generated:

summary_by_year.csv: Yearly stats

defense_mechanism_analysis.csv: Attack-defense matrix

PNG plots: trends, boxplots, feature importance

📈 Sample Visuals
Financial Loss Trends

Yearly Distributions

XGBoost Feature Importance

Attack-Defense Heatmap
(Knit to regenerate)

🗄️ Dataset
Global_Cybersecurity_Threats_2015-2024.csv (251KB): 10 columns including Country, Attack Type, Financial Loss (0.5-100M USD), Affected Users, Resolution Time (hours).
​

Author
Harsh Malviya
MS Data Science Candidate, UMass Dartmouth
Portfolio | GitHub | LinkedIn

Citation
text
Malviya, H. (2025). Cyber Attack Financial Impact Analysis (2015-2024). 
GitHub repository: harsh-stack/Cyber-Attack-Analysis.
