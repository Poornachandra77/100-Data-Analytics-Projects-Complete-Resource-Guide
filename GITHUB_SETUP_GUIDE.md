# 🚀 GitHub Setup Guide — 100 Data Analytics Projects

A step-by-step guide to set up all 100 repositories on your GitHub account
(**https://github.com/Poornachandra77**) and maximize stars for your O1 visa application.

---

## Phase 1 — Create the Master Repository

### Step 1: Create the main repo on GitHub

1. Go to **https://github.com/new**
2. Repository name: `100-data-analytics-projects`
3. Description: `📊 100 end-to-end Data Analytics, ML, and Business Intelligence projects with code, datasets, and visualizations`
4. Set to **Public**
5. ✅ Add a README file
6. License: **MIT**
7. Click **Create repository**

### Step 2: Push the README

```bash
git clone https://github.com/Poornachandra77/100-data-analytics-projects.git
cd 100-data-analytics-projects

# Copy the README.md from this folder into the cloned repo
# Then commit and push
git add README.md
git commit -m "Add master README with 100 project list"
git push origin main
```

---

## Phase 2 — Create Individual Project Repos

For each of the 100 projects, create a separate repository. Here is the naming convention:

| Repo Name | Example |
|-----------|---------|
| `customer-churn-prediction` | Project #1 |
| `house-price-prediction` | Project #2 |
| ... | ... |

### Quick script to create all repos (using GitHub CLI)

First install GitHub CLI: https://cli.github.com/

```bash
# Login
gh auth login

# Create each repo (run this for each project)
gh repo create Poornachandra77/customer-churn-prediction \
  --public \
  --description "Predict telecom customer churn using XGBoost, Random Forest | Dataset: Kaggle Telco" \
  --clone
```

Or use the bulk creation script: `scripts/create_all_repos.sh`

---

## Phase 3 — Project Folder Structure (for EVERY repo)

Each individual project repo should have this structure:

```
repo-name/
├── README.md                 ← Professional, detailed README (see template)
├── notebook.ipynb            ← Main Jupyter Notebook
├── requirements.txt          ← Python dependencies
├── data/
│   └── README.md            ← Instructions to download dataset
├── src/
│   ├── __init__.py
│   ├── preprocess.py
│   ├── model.py
│   └── visualize.py
└── outputs/
    ├── plots/               ← Saved charts and visualizations
    └── models/              ← Saved model files (.pkl, .h5)
```

---

## Phase 4 — README Template (use for ALL 100 repos)

Copy this template for every project's README:

```markdown
# [Project Title]

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![Status](https://img.shields.io/badge/Status-Complete-green)
![Dataset](https://img.shields.io/badge/Dataset-[Source]-orange)

## 📌 Overview
[2-3 sentence description of the project and business problem it solves]

## 🎯 Objectives
- Objective 1
- Objective 2
- Objective 3

## 📊 Dataset
- **Source:** [Dataset name and link]
- **Size:** [Number of rows × columns]
- **Key Features:** [Feature1, Feature2, Feature3]

## 🛠️ Tech Stack
`Python` `Scikit-learn` `Pandas` `Matplotlib` `[Other tools]`

## 🔍 Methodology
1. Data Loading & Exploration
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Training & Evaluation
6. Results & Insights

## 📈 Key Results
| Metric | Score |
|--------|-------|
| Accuracy | XX% |
| F1 Score | 0.XX |
| AUC-ROC | 0.XX |

## 📸 Visualizations
[Add screenshots of your key charts here]

## 🚀 How to Run
```bash
git clone https://github.com/Poornachandra77/[repo-name].git
cd [repo-name]
pip install -r requirements.txt
jupyter notebook notebook.ipynb
```

## 📂 File Structure
```
├── notebook.ipynb
├── requirements.txt
├── data/
├── src/
└── outputs/
```

## 🔗 Related Projects
- [Link to related project 1]
- [Link to related project 2]
```

---

## Phase 5 — Getting Stars (O1 Visa Strategy)

### High-Impact Actions

1. **Post on LinkedIn** — Share each project with a key insight or chart.
   Sample post:
   > "Just published my analysis of [Topic] 📊
   > Key finding: [Interesting insight]
   > Full code + notebook: [GitHub link]
   > #DataScience #Python #MachineLearning"

2. **Post on Twitter/X** — Tag relevant data science accounts.

3. **Share on Reddit** — Post in r/datascience, r/MachineLearning, r/learnpython

4. **Submit to Kaggle** — Link your notebooks on Kaggle discussions

5. **Awesome Lists** — Submit a PR to these popular lists:
   - https://github.com/academic/awesome-datascience
   - https://github.com/josephmisiti/awesome-machine-learning
   - https://github.com/krispo/awesome-haskell (use as model)

6. **Dev.to / Medium articles** — Write a blog post about each project

7. **Cross-link repositories** — Each repo's README should link to the master repo

### Topics to add to each repo (increases discoverability)
Go to each repo → ⚙️ Settings → Topics → Add:
```
data-science, machine-learning, python, jupyter-notebook,
pandas, scikit-learn, data-analysis, data-visualization,
deep-learning, nlp, tensorflow, pytorch
```

---

## Phase 6 — Priority Order (Start with these for maximum impact)

These projects tend to attract the most stars. Do them first:

| Priority | Project | Why High Impact |
|----------|---------|-----------------|
| 🥇 1 | Customer Churn Prediction | Very popular, well-understood business problem |
| 🥇 2 | Credit Card Fraud Detection | High interest, imbalanced learning techniques |
| 🥇 3 | Stock Price Forecasting with LSTM | Popular topic, complex implementation |
| 🥇 4 | Sentiment Analysis on Twitter | Trendy, social media relevance |
| 🥇 5 | RAG-Based Document Q&A | Hottest AI trend right now |
| 🥇 6 | COVID-19 Global Analysis | Timeless, widely referenced |
| 🥇 7 | Fake News Detection | High social relevance |
| 🥇 8 | Sales Forecasting with Prophet | Practical business use case |
| 🥇 9 | Market Basket Analysis | Classic, widely taught |
| 🥇 10 | A/B Testing Framework | Used by every tech company |

---

## O1 Visa Evidence Tips

Once your repos have stars, document for your O1 application:

1. **Screenshot total stars** across all repos
2. **GitHub profile stats** using https://github-readme-stats.vercel.app
3. **Contribution graph** showing consistent activity
4. **Forks count** — shows others are building on your work
5. **Repository traffic** (Settings → Insights → Traffic) — shows views & clones

Add to your GitHub profile README:

```markdown
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Poornachandra77&show_icons=true&theme=radical)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Poornachandra77&layout=compact)
```

---

*Good luck with your O1 visa application! 🍀*
