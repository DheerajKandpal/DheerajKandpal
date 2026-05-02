<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=180&section=header&text=Dheeraj%20Kandpal&fontSize=52&fontColor=fff&animation=twinkling&fontAlignY=42" width="100%"/>

### 🏦 Data & Python Engineer &nbsp;·&nbsp; Fintech Pipelines &nbsp;·&nbsp; Power BI

</div>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=3800&pause=900&color=58A6FF&center=true&vCenter=true&width=750&lines=Data+%26+Python+Engineer+%40+Surepass;Processing+10%2C000%2B+API+records+daily+%E2%9A%99%EF%B8%8F;Building+AI+Agents+%7C+FastAPI+%7C+PostgreSQL;Fintech+pipelines+that+actually+run+in+production+%F0%9F%9A%80" alt="Typing SVG" />

</div>

<br/>

<div align="center">

[![Profile Views](https://komarev.com/ghpvc/?username=DheerajKandpal&style=flat-square&color=58A6FF&label=Profile+Views)](https://github.com/DheerajKandpal)
&nbsp;&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dheeraj%20Kandpal-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dheeraj-kandpal)
&nbsp;&nbsp;
[![Gmail](https://img.shields.io/badge/Gmail-dheerajkandpal11111-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:dheerajkandpal11111@gmail.com)
&nbsp;&nbsp;
[![Open To Work](https://img.shields.io/badge/%F0%9F%9F%A2_Open_To-Data_%26_Python_Roles-22C55E?style=flat-square)](https://www.linkedin.com/in/dheeraj-kandpal)

</div>

---

## ⚡ What I Do

> **Data & Python Engineer @ Surepass** — fintech data intelligence company.
> I build production batch pipelines processing identity verification records at scale.
> RC · GST · PAN · MCA · Land Records. Real infrastructure. Every day.

```
📍  Delhi NCR, India  |  🏦  Fintech / Data Intelligence  |  🚀  Open to Data & Python roles
```

---

## 🔧 Production Pipeline Architecture

```
┌──────────────────────────────────────────────────────────────────────┐
│                    SUREPASS BATCH PIPELINE                           │
├──────────────────────────────────────────────────────────────────────┤
│                                                                      │
│  📥  INPUT      CSV — 10,000+ rows  (RC, GST, PAN, MCA numbers)     │
│         │                                                            │
│         ▼                                                            │
│  ⚡  FETCH      ThreadPoolExecutor — concurrent REST API calls       │
│                 → ~70% faster than sequential I/O                    │
│         │                                                            │
│         ▼                                                            │
│  🧹  PARSE      ujson.loads() → flatten nested JSON → DataFrame     │
│         │                                                            │
│         ▼                                                            │
│  🔍  VALIDATE   Chassis matching · PAN/Aadhaar masking · error flags │
│         │                                                            │
│         ▼                                                            │
│  📤  EXPORT     Annotated CSV → Power BI dashboard pipeline         │
│                                                                      │
└──────────────────────────────────────────────────────────────────────┘
```

---

## 📊 Production Numbers

| Metric | Detail |
|:---|:---|
| 🔁 Daily records | **10,000+ identity API calls per batch run** |
| ⚡ Speed gain | **~70% faster with ThreadPoolExecutor vs sequential** |
| 🗂️ Domains | **Vehicle RC · GST · PAN · MCA · Land Records** |
| 🔐 Security | **Aadhaar + PAN field masking on every export** |
| 📤 Output | **Annotated CSV → Power BI ingestion ready** |

---

## 🛠️ Tech Stack

<div align="center">

[![Skills](https://skillicons.dev/icons?i=python,fastapi,selenium,mysql,postgresql,mongodb,git,github,vscode,pycharm,jupyter,linux&theme=dark)](https://skillicons.dev)

</div>

<br/>

**Python Ecosystem**
&nbsp;
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![ujson](https://img.shields.io/badge/ujson-FF6F00?style=flat-square&logo=python&logoColor=white)
![requests](https://img.shields.io/badge/requests-306998?style=flat-square&logo=python&logoColor=white)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4B8BBE?style=flat-square&logo=python&logoColor=white)
![Pydantic v2](https://img.shields.io/badge/Pydantic_v2-E92063?style=flat-square&logo=pydantic&logoColor=white)
![concurrent.futures](https://img.shields.io/badge/concurrent.futures-58A6FF?style=flat-square&logo=python&logoColor=white)

**BI & Analytics**
&nbsp;
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Advanced%20Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Window_Fns_|_CTEs-4479A1?style=flat-square&logo=postgresql&logoColor=white)

---

## 📌 Featured Projects

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/DheerajKandpal/ai-job-agent">🤖 AI Job Agent</a></h3>
      <p>Autonomous AI system that discovers jobs, generates tailored resumes & cover letters, and applies automatically with tracking.</p>
      <img src="https://img.shields.io/badge/Python-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
      <img src="https://img.shields.io/badge/LLM-AI%20Agent-FF6B35?style=flat-square&logo=openai&logoColor=white"/>
      <img src="https://img.shields.io/badge/DB-PostgreSQL-4479A1?style=flat-square&logo=postgresql&logoColor=white"/>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/DheerajKandpal/sureflow-data-enrichment">⚙️ SureFlow Data Enrichment</a></h3>
      <p>Production-grade batch data enrichment pipeline with pluggable provider architecture, demo mode, and FastAPI backend.</p>
      <img src="https://img.shields.io/badge/Python-Backend-3776AB?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/FastAPI-Data_Pipeline-009688?style=flat-square&logo=fastapi&logoColor=white"/>
      <img src="https://img.shields.io/badge/Focus-Fintech_Infra-58A6FF?style=flat-square"/>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/DheerajKandpal/ecommerce-sales-analysis">🗄️ E-Commerce Sales Analysis</a></h3>
      <p>Deep SQL analysis of e-commerce data — window functions, CTEs, revenue segmentation, customer cohort analysis.</p>
      <img src="https://img.shields.io/badge/SQL-PostgreSQL-4479A1?style=flat-square&logo=postgresql&logoColor=white"/>
      <img src="https://img.shields.io/badge/Focus-Business_Intelligence-58A6FF?style=flat-square"/>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/DheerajKandpal/IPL-Cricket-2008-2023-">📊 IPL Cricket Analytics</a></h3>
      <p>15 years of IPL data — player performance trends, team win rates, batting/bowling stats using Python & Jupyter EDA.</p>
      <img src="https://img.shields.io/badge/Python-Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white"/>
      <img src="https://img.shields.io/badge/Focus-Sports_Analytics-22C55E?style=flat-square"/>
    </td>
  </tr>
</table>

---

## 📈 GitHub Stats

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=DheerajKandpal&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9&ring_color=58A6FF" />
&nbsp;
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DheerajKandpal&layout=compact&langs_count=6&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" />

</div>

<div align="center">

<img src="https://streak-stats.demolab.com?user=DheerajKandpal&theme=github-dark-blue&hide_border=true&background=0D1117&ring=58A6FF&fire=FF6B35&currStreakLabel=58A6FF&sideLabels=8B949E&dates=8B949E&stroke=21262D" />

</div>

<div align="center">
<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=DheerajKandpal&theme=github-compact&hide_border=true&bg_color=0D1117&color=58A6FF&line=58A6FF&point=FF6B35&area=true&area_color=58A6FF" />
</div>

---

## 🌱 Roadmap

```python
roadmap = {
    "NOW   🔵" : [
        "Python internals — decorators, generators, async/await",
        "SQL mastery — window functions, CTEs, query optimization",
        "Advanced DAX patterns for Power BI",
    ],
    "NEXT  🟡" : [
        "ML pipelines: pandas → scikit-learn → model evaluation",
        "Docker + GitHub Actions CI/CD",
        "GCP BigQuery / cloud data warehousing",
    ],
    "2027  🔴" : [
        "MLOps — Airflow, model versioning, feature stores",
        "Spark / distributed processing at scale",
    ],
}
```

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/DheerajKandpal/DheerajKandpal/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/DheerajKandpal/DheerajKandpal/output/github-contribution-grid-snake.svg"/>
  <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/DheerajKandpal/DheerajKandpal/output/github-contribution-grid-snake.svg"/>
</picture>

</div>

---

## 🤝 Let's Connect

<div align="center">

<a href="https://www.linkedin.com/in/dheeraj-kandpal">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
&nbsp;
<a href="mailto:dheerajkandpal11111@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-Reach%20Out-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
&nbsp;
<a href="https://github.com/DheerajKandpal">
  <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br/><br/>

**Open to:** Data Analyst &nbsp;·&nbsp; Python Developer &nbsp;·&nbsp; Data Engineer roles &nbsp;·&nbsp; India 🇮🇳

</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" width="100%"/>
<sub><i>"I don't just analyze data — I build the infrastructure that makes analysis possible."</i></sub>
</div>
