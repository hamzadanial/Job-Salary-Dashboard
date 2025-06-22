# job-salary-dashboard

Bokeh app that lets you filter and visualize job-salary data by country, role, experience, work mode, and year.

## Quick start
```bash
git clone https://github.com/hamzadanial/job-salary-dashboard.git
cd job-salary-dashboard
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt    # needs bokeh, pandas, numpy
bokeh serve dashboard1.ipynb --show --port 5010


## ✨ Key Features
| Chart | Insight |
|-------|---------|
| 🌍 **World Map** | Average salary by employee residence (hover for values). |
| 📊 **Bar Plot** | Salary vs. experience level, with country filter. |
| 🧩 **Grouped Bars** | Cross-tab of work setting × job category. |
| 📈 **Trend Line** | Salary evolution across years, filterable by job category. |
| 🥧 **Pie Chart** | Salary share by employment type. |
| 🏃 **Histogram** | Overall salary distribution. |

All widgets are linked; updating a filter instantly refreshes the visualizations.
