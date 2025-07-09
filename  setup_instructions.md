# 🛠️ 12DayDataSeries Setup Instructions

Welcome to **12DayDataSeries** — a 12-day hands-on machine learning journey where I build an intelligent Mission Control AI using simulated space mission data.  
Each day introduces a new data science concept applied to a growing, evolving project.

---

## ✅ 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/12DayDataSeries.git
cd 12DayDataSeries

```

## 🐍 2. Set Up a Virtual Environment (Recommended)

### Mac/Linux:
```bash
python3 -m venv venv
source venv/bin/activate
``` 
### Windows (Command Prompt):
``` bash
python -m venv venv
venv\Scripts\activate
```

## 📦 3. Install Required Python Packages
With the virtual environment active:
``` bash
Copy
Edit
pip install -r requirements.txt
```

Main dependencies:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- jupyter

## 🚀 4. Launch the Project
``` bash
jupyter notebook
```
Then open the notebook as: 
notebook/0_data_simulation.ipynb

## 📁 Project Structure

``` bash 
12DayDataSeries/
├── notebook/
│   ├── 0-data-simulation/             # Day 0 notebook: simulation + setup
│   ├── 1-linear-regression/                      # Day 1 notebook: linear regression
│   └── ...                            # More days to come
├── notebook/data/csv/                # Generated datasets (e.g., mission_data.csv)
├── requirements.txt                  # Python dependencies
├── README.md                         # Project overview
└── setup_instructions.md             # Setup guide (this file)

```
## 💡 Notes
You’ll build on this project day-by-day.

Each notebook builds on the last, applying new ML concepts to the same dataset.

Final goal: a smart, interpretable, and context-aware Mission Control AI.

## 🧠 Need Help?
Try:

```bash

pip install --upgrade pip
```
If something breaks, check the repo's Issues tab or feel free to reach out on LinkedIn!



