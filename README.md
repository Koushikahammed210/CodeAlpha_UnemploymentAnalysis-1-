📊 CodeAlpha – Unemployment Analysis with Python
Task 2 of the CodeAlpha Data Science Internship.

📌 Objective
Analyze India's unemployment data for 2020 — explore trends across states andzones, measure the impact of the Covid-19 lockdown, and derive insightsthat could inform economic and social policies.

📊 Dataset
File: Unemployment_Rate_upto_11_2020.csv
Coverage: Jan 2020 – Oct/Nov 2020, monthly data per state
Features: Region (state), Date, Estimated Unemployment Rate (%),Estimated Employed, Estimated Labour Participation Rate (%), Zone
Cleaning: stripped extra spaces from column names, renamed Region.1→ Zone, parsed dates, checked for missing values
🛠️ Tools & Libraries
Python
Pandas (data cleaning & aggregation)
Matplotlib, Seaborn (visualization)

🔄 Workflow
Load & clean the data (column name fixes, date parsing)
National trend — monthly average unemployment over 2020
COVID-19 impact — compare pre-lockdown (Jan–Mar) vs lockdown (Apr–Jun) rates
State × Month heatmap to spot the worst-hit states and months
Top 5 worst-hit states during the lockdown
Employment tracking — total employed people per month (job losses & recovery)
Zone comparison — North / South / East / West / Northeast averages

📈 Results
Metric	Value
Pre-lockdown avg (Jan–Mar 2020)	~8%
Lockdown avg (Apr–Jun 2020)	~22%
Impact	Unemployment roughly tripled
Jobs lost in April 2020 alone	~118 million (393M → 275M employed)
Top 5 worst-hit states (Apr–Jun 2020): Puducherry (~46%), Jharkhand (~43%), Bihar (~36%), Haryana (~32%), Tamil Nadu (~31%)

🔍 Key Insights
The April 2020 nationwide lockdown caused a dramatic unemployment spike,with a slow recovery through late 2020.
Employment collapsed from ~393M (March) to ~275M (April) — recovering to~395M by October.
Unemployment rates were not uniform: northern and eastern states were hitharder on average than southern and western zones.
✅ Policy insight: the scale and speed of job losses highlights the needfor social safety nets, MSME support, and crisis-ready employment schemes.
📁 Project Structure
CodeAlpha_UnemploymentAnalysis/├── Unemployment_Analysis.ipynb  # full code + outputs├── trend.png                    # national monthly trend├── heatmap.png                  # state × month heatmap├── top5.png                     # worst-hit states├── employed.png                 # employed people over time├── zones.png                    # zone comparison└── README.md

▶️ How to Run
Open the notebook in Google Colab or Jupyter and run all cells.Make sure Unemployment_Rate_upto_11_2020.csv is in the same folder(upload it first in Colab).
