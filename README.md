# COVID-19 Global Data Tracker

A Jupyter Notebook–based project that analyzes global COVID-19 trends in cases, deaths, and vaccinations using data from [Our World in Data](https://covid.ourworldindata.org/data/owid-covid-data.csv).

---

## 🔍 Features

- **Data Cleaning**  
  Processes raw OWID CSV to produce a clean, analysis-ready dataset.
- **Exploratory Data Analysis (EDA)**  
  Time-series trends for cases, deaths, and vaccination rates.
- **Comparative Analysis**  
  Compare metrics across multiple countries.
- **Visualizations**  
  Line charts, bar plots, and choropleth maps generated in a Jupyter Notebook.

---

## 🚀 Quick Start

### 1. Clone the repo

```bash
git clone https://github.com/MuganziJames/my_covid_data_analysis_project.git
cd my_covid_data_analysis_project
```

### 2. Create & activate a virtual environment

```bash
python3 -m venv venv
# On macOS/Linux:
source venv/bin/activate
# On Windows (PowerShell):
.\venv\Scripts\Activate.ps1
```

### 3. Install dependencies

First, create a `requirements.txt` (if you don’t already have one):

```bash
pip install pandas numpy matplotlib seaborn plotly ipywidgets
pip freeze > requirements.txt
```

Then install:

```bash
pip install -r requirements.txt
```

### 4. Launch the Notebook

```bash
jupyter notebook covid19_global_data_tracker.ipynb
```

---

## 📂 Project Structure

```
my_covid_data_analysis_project/
├── covid19_global_data_tracker.ipynb   # Main analysis notebook
├── owid-covid-data.csv                  # Raw data from Our World in Data
├── cleaned_covid_data.csv               # Cleaned dataset used in analysis
├── requirements.txt                     # Python dependencies
└── README.md                            # This file
```

---

## 📋 Usage

1. Open and run all cells in `covid19_global_data_tracker.ipynb`.
2. Follow the notebook’s step-by-step analysis:
   - Data loading & cleaning
   - Time-series plotting
   - Country comparisons
   - Choropleth mapping

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m "Add some feature"`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

## 📝 License

This project is released under the MIT License.

---

_Happy analyzing!_
