# Data Analytics Using NumPy and Python

### A practical MBA workshop at Amity University, Lucknow

**9 October 2026 · 2 hours · Instructor: Zaid Kamil**

![Python](https://img.shields.io/badge/Python-3-3776AB?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Arrays-013243?logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Analytics-150458?logo=pandas&logoColor=white)
![Audience](https://img.shields.io/badge/Audience-MBA_students-00897B)

![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)
[![License: MIT](https://img.shields.io/badge/License-MIT-green)](LICENSE)

Learn to turn business data into useful decisions with **Python, NumPy, and Pandas**. We use small, fictional sales examples to explore revenue, profitability, branch performance, and data quality.

## What you will learn

- Use NumPy arrays for calculations, summaries, and comparisons.
- Use Pandas to inspect, clean, filter, and summarise transaction data.
- Distinguish revenue, gross profit, and margin.
- Explain the assumptions and limitations behind a management report.
- Understand eigenvalues at an introductory level and recognise supporting Python tools.

## Start here: teaching notebooks

| Notebook | Coverage | Run online |
|---|---|---|
| [Python refresher + NumPy](notebooks/01_numpy_business_essentials.ipynb) | Arrays, calculations, statistics, filtering, branch comparison | [Open in Colab](https://colab.research.google.com/github/zaid-kamil/Data-analytics-using-numpy-and-python-at-Amity-Lucknow/blob/main/notebooks/01_numpy_business_essentials.ipynb) |
| [Pandas sales analysis](notebooks/02_pandas_sales_analysis.ipynb) | CSV loading, cleaning, revenue/profit, grouping, ranking, exercises | [Open in Colab](https://colab.research.google.com/github/zaid-kamil/Data-analytics-using-numpy-and-python-at-Amity-Lucknow/blob/main/notebooks/02_pandas_sales_analysis.ipynb) |
| [Closing appendix](notebooks/03_eigenvalues_and_python_toolkit.ipynb) | Eigenvalues, two examples per requested tool, optional self-study | [Open in Colab](https://colab.research.google.com/github/zaid-kamil/Data-analytics-using-numpy-and-python-at-Amity-Lucknow/blob/main/notebooks/03_eigenvalues_and_python_toolkit.ipynb) |

The notebooks are self-contained. Run them in order; within each notebook, run cells from top to bottom. Every notebook includes an instructor introduction, badges, small samples, and a connection invitation.

## Student practice and solutions

| Resource | Purpose | Run online |
|---|---|---|
| [Student practice notebook](notebooks/04_student_practice.ipynb) | Ten tasks with prompts, data loading, and empty answer cells | [Open in Colab](https://colab.research.google.com/github/zaid-kamil/Data-analytics-using-numpy-and-python-at-Amity-Lucknow/blob/main/notebooks/04_student_practice.ipynb) |
| [Solved notebook](solutions/04_practice_solutions.ipynb) | Worked code, interpretation, and expected checkpoints | [Open in Colab](https://colab.research.google.com/github/zaid-kamil/Data-analytics-using-numpy-and-python-at-Amity-Lucknow/blob/main/solutions/04_practice_solutions.ipynb) |
| [Retail sales CSV](datasets/retail_sales_practice.csv) | Region/product profitability and a pricing scenario | Download from GitHub |
| [Marketing campaigns CSV](datasets/marketing_campaigns_practice.csv) | CTR, CPC, CPL, CAC, and ROAS analysis | Download from GitHub |

Start with the practice notebook, run its data-loading cell, and complete the exercises in order. Use the solved notebook after attempting your answers. The [dataset guide](datasets/README.md) explains columns and deliberate data-quality issues. Budget 30–45 minutes for the full practice lab outside the main session.

## Two-hour delivery plan

| Minutes | Topic |
|---|---|
| 0–10 | Introduction, business problem, and setup check |
| 10–20 | Python essentials: lists, dictionaries, libraries, and packages |
| 20–45 | NumPy business essentials |
| 45–85 | Pandas sales and profitability analysis |
| 85–95 | MBA mini-case and discussion |
| 95–105 | Eigenvalue problems and a covariance example |
| 105–115 | Selected Python tools from the appendix |
| 115–120 | Recap and questions |

**Core:** notebooks 1 and 2. **Optional closing material:** notebook 3. The tools appendix gives two short examples or scenarios for each requested topic; use selected examples in class and leave the rest for self-study.

## Run the notebooks

### Option A: Google Colab

Use a notebook’s **Open in Colab** link. No local installation is required. Sign into Google when prompted, then use **Runtime → Run all**, or **Shift + Enter** to run one cell at a time.

### Option B: local JupyterLab

Install Python 3.10 or newer, clone this repository, and open a terminal in its folder:

```bash
python -m venv .venv
```

Activate the environment using the command for your system:

```powershell
# Windows PowerShell
.venv\Scripts\Activate.ps1
```

```bash
# macOS / Linux
source .venv/bin/activate
```

Then install the learning dependencies and launch JupyterLab:

```bash
python -m pip install -r requirements.txt
python -m jupyterlab
```

Open the `notebooks` folder and start with notebook 1. The optional tools discussed in notebook 3 are not required to execute its cells.

## Business case

Compare fictional stationery sales across Lucknow, Delhi, and Kanpur. The Pandas example includes a duplicate order and a missing units value so we can practise explaining data-cleaning decisions.

Answer: **Which region leads revenue? Which product leads profit? Does the highest-revenue region also lead in profit?**

All currency values are INR. Gross profit excludes overheads and taxes. Price-change examples assume unchanged demand. These are teaching examples, not real company records.

## Additional topics requested by the university

Notebook 3 covers bug tracking, virtual environments, pdoc, Komodo Edit, debugging using pydbgr (with a Python 3 `pdb` demonstration), IPython, PyUnit/`unittest`, isort, Mercurial, libraries, dictionaries, packages, and eigenvalue problems. Interactive debugger and installation commands are shown as reference text rather than executed automatically.

### Your instructor: Zaid Kamil

I have over 12 years of experience in software development, technical education, and technology leadership. My expertise includes Python, backend development, AI and machine learning, automation, Flutter, and Android development. I have authored two technology books published by BPB Publications: **My First Mobile App for Students** and **Flutter Solutions for Web Developers**.

### Stay connected

If this session helped you, **follow [Zaid Kamil on GitHub](https://github.com/zaid-kamil)** for more learning resources and **[connect on LinkedIn](https://linkedin.com/in/zaid-kamil-94211a40)**. Mention the Amity Lucknow workshop in your connection request.

[![Follow on GitHub](https://img.shields.io/badge/GitHub-Follow_Zaid-181717?logo=github&logoColor=white)](https://github.com/zaid-kamil)
[![Connect on LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2)](https://linkedin.com/in/zaid-kamil-94211a40)

You can also star this repository to find the notebooks again.

## License

This repository uses the [MIT License](LICENSE).
