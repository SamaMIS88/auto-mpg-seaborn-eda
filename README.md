# 🚗 Auto MPG: Seaborn Practice

![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Data%20Viz-4c72b0)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)

A hands-on exploration of the classic **Auto MPG dataset** using **Seaborn**. Every plot type from my Seaborn course is applied to real data, with short written insights under each chart.

---

## 📌 Overview

| | |
|---|---|
| **Dataset** | Auto MPG, 398 cars (1970-1982) |
| **Origins** | USA (249), Japan (79), Europe (70) |
| **Key columns** | `mpg`, `cylinders`, `displacement`, `horsepower`, `weight`, `acceleration`, `model_year`, `origin` |
| **Goal** | Practice Seaborn and learn what drives fuel efficiency |

---

## 📂 Project Structure

```
auto-mpg-seaborn-eda/
├── data/
│   └── mpg_raw.csv
├── notebooks/
│   ├── distributions.ipynb     # Histogram, KDE, Jointplot, Pairplot
│   ├── bar_and_count.ipynb     # Barplot, Countplot
│   ├── relational.ipynb        # Relplot
│   └── categorical.ipynb       # Catplot, Swarm, Box, Violin
├── README.md
└── .gitignore
```

---

## 📊 What's Inside

| Notebook | Plots covered |
|---|---|
| **Distributions** | `histplot`, `kdeplot`, `jointplot`, `pairplot` |
| **Bar & Count** | `barplot`, `countplot` |
| **Relational** | `relplot` |
| **Categorical** | `catplot`, `swarmplot`, `boxplot`, `violinplot` |

---

## 🔍 Key Findings

- **Heavier cars get lower mpg** (correlation of about -0.83 between weight and mpg).
- **USA cars are the least efficient**: average of about 20 mpg, versus about 30 for Japan and 28 for Europe. They are also the heaviest and most powerful (about 119 hp on average).
- **More cylinders means lower mpg** in every origin.
- **Efficiency improved over time.** Cars under 15 mpg disappear after 1976, and cars over 30 mpg dominate 1980-82.
- **8-cylinder cars faded out**, from 18 in 1970 to almost none after 1980, while 4-cylinder cars took over.
- **Best and worst picks (by mpg for their group):**
  - ✅ Datsun 280-ZX and Oldsmobile Cutlass LS
  - ❌ Mazda RX2 Coupe and Mazda RX3

> ⚠️ Groups with few cars (3 and 5 cylinders) have wide error bars, so those insights are weak.

---

## 🚀 Getting Started

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/auto-mpg-seaborn-eda.git
cd auto-mpg-seaborn-eda

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# 3. Launch the notebooks
jupyter notebook notebooks/
```

Each notebook loads the data with `pd.read_csv("../data/mpg_raw.csv")` and runs on its own.

---

## 🛠️ Tech Stack

- **Python 3.13**
- **Pandas** and **NumPy** for data handling
- **Seaborn** and **Matplotlib** for visualization
- **Jupyter / VS Code** for notebooks
- **Git** for version control

---

## 📝 Notes

- The data was used as is. The only gap is 6 missing `horsepower` values, which Seaborn skips automatically.
- The project follows a Seaborn course, with one section per lecture.

---

## 👤 Author

**Sama Alshehri**
MIS student (Data Analytics track)
[LinkedIn](https://www.linkedin.com/in/your-profile) · [GitHub](https://github.com/your-username)
