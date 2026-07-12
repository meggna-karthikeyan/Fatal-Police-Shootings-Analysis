<p align="center">
  <img src="images/First%20Image.png" alt="Fatal Police Shootings" width="100%">
</p>

# 🚔 Fatal Police Shootings | Data Visualization & Policy Analysis

## 📝 Overview

This project explores **fatal police shootings across the United States from 2015 to 2022**, turning 8,000+ recorded incidents into an interactive **Tableau dashboard** that reveals *where* these shootings happen, *who* is most affected, and *under what circumstances*. The findings are framed as a **data memo to the U.S. Department of Justice**, translating raw numbers into evidence-based recommendations for training, policy, and community reform.

The goal is simple: move past headlines and let the data tell the story — so that reform can be guided by patterns, not perception.


## 📦 Dataset Source

The dataset comes from **[Data.World – Fatal Police Shootings](https://data.world/data-society/fatal-police-shootings)** and documents every fatal police shooting in the U.S. between **2015 and 2022**, with one row per incident.

| Column | Description |
|--------|-------------|
| `id`, `name`, `date` | Unique identifier, victim name, and date of incident |
| `manner_of_death` | Shot, or shot & Tasered |
| `armed` | Whether the individual was armed and with what |
| `age`, `gender`, `race` | Victim demographics |
| `city`, `state`, `longitude`, `latitude` | Location of the incident |
| `signs_of_mental_illness` | Whether signs of mental illness were present |
| `threat_level` | Perceived threat: attack / other / undetermined |
| `flee`, `body_camera` | Fleeing status and body-camera presence |


## 🛠 Technologies Used

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![CSV](https://img.shields.io/badge/CSV-Data-1D6F42?style=for-the-badge&logo=files&logoColor=white)
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-4B8BBE?style=for-the-badge&logo=chartdotjs&logoColor=white)
![Data Storytelling](https://img.shields.io/badge/Data%20Storytelling-FF6F61?style=for-the-badge&logo=bookstack&logoColor=white)


## 🎯 Objectives

1. **Demographics** — What are the age, gender, and racial patterns among victims?
2. **Geography** — How do fatal shootings vary across states and regions of the country?
3. **Circumstances** — What role do weapons, perceived threat level, signs of mental illness, and body cameras play?


## 🔬 Methodology

- **Aggregation & granularity** — data grouped by state, age band, and weapon type to surface totals.
- **Ranking & sorting** — states and weapons ordered by incident count to expose the leaders.
- **Marks card** — color and detail marks used to separate demographics, states, and weapon types.
- **Date filtering** — a date function scopes the analysis to the 2015–2022 window.
- **Interactivity** — a state filter lets users drill into any state and update every chart dynamically.


## 📈 Key Findings

| Insight | Detail |
|---------|--------|
| 🗺️ **Geographic concentration** | The **top 10 states account for 4,245 shootings — nearly 53%** of the **8,002** national total. **California (1,143)**, **Texas (732)**, and **Florida (509)** lead the country. |
| 👥 **Age** | **Young adults aged 15–30** are the most affected group, forming the clear peak of the age distribution. |
| ⚖️ **Racial disparity** | Victims span White, Black, and Hispanic groups, with the data pointing to meaningful racial disparities in who is affected. |
| 🔫 **Weapons** | **Guns are by far the most common weapon** involved, followed by knives — most incidents occur when the individual is perceived as armed. |
| 📉 **Trend over time** | Annual totals stayed **relatively stable from 2015 to 2022**, suggesting existing measures have not meaningfully reduced incidents. |

### 🏆 Top 10 States for Fatal Police Shootings
<p align="center">
  <img 
    src="images/Top%2010%20States.png"
    alt="Top 10 States"
    width="750"
  >
</p>

<p>
  California, Texas, and Florida dominate the national picture, together making up a disproportionate share of incidents.
</p>

### 👥 Demographics of the Victims
<p align="center">
  <img 
    src="images/Demographics%20of%20the%20Victims.png"
    alt="Demographics of the Victims"
    width="750"
  >
</p>

<p>
  The distribution peaks sharply among young adults aged 15–30, a critical life stage of education, work, and family.
</p>

### 🔫 Weapons Used in the Shootings
<p align="center">
  <img 
    src="images/Weapons%20Used%20in%20the%20Shootings.png"
    alt="Weapons Used"
    width="750"
  >
</p>

<p>
  Firearms are the most frequently involved weapon, underscoring the need for stronger de-escalation strategies in armed encounters.
</p>


## 📊 Interactive Dashboard

The full story comes together in a single interactive **Tableau dashboard** — choose any state to instantly update every view.

![Fatal Police Shootings Dashboard](images/Fatal%20Police%20Shootings.png)

> 📂 **Explore it yourself:** download **`Fatal Police Shootings.twbx`** and open it in the free [Tableau Reader](https://www.tableau.com/products/reader) or Tableau Desktop.


## 🎯 Recommendations & Implications

1. **Targeted training** — roll out de-escalation and mental-health-response training in the highest-incident states (California, Texas, Florida).
2. **Policy reforms** — standardize use-of-force policies nationwide, with body cameras, comprehensive reporting, and independent investigations.
3. **Community engagement** — invest in community-policing initiatives that rebuild trust in the areas hit hardest.


## 📌 Future Scope

- Extend the analysis with data beyond 2022 to track the effect of recent reforms.
- Layer in socioeconomic and policing-policy data to explain *why* certain states rank higher.
- Add predictive modeling to flag high-risk conditions and support prevention efforts.


> _Behind every data point is a life — this project turns those numbers into a case for accountability and reform._

