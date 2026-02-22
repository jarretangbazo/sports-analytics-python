# Sports Analytics

A Python-based sports analytics project developed as part of a structured class curriculum.

---

## Project Structure

```
sports-analytics/
├── notebooks/
├── data/
│   ├── raw/
│   └── output/
├── visualizations/
├── resources/
└── requirements.txt
```

- `notebooks/` — Jupyter notebooks organized by weekly module
- `data/raw/` — original, unmodified datasets (not tracked by Git)
- `data/output/` — cleaned and processed data files (not tracked by Git)
- `visualizations/` — saved charts and figures
- `resources/` — reference documents

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/jarretangbazo/sports-analytics-python.git
cd sports-analytics-python
```

### 2. Create and Activate the Virtual Environment

```bash
python -m venv sports-analytics-env
source sports-analytics-env/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter

```bash
jupyter notebook
```

---

## Dependencies

Key packages used in this project:

- `pandas` — data manipulation and analysis
- `numpy` — numerical computing
- `matplotlib` / `seaborn` — data visualization
- `statsmodels` — statistical modeling and econometrics
- `jupyter` — interactive notebook environment

A full list of dependencies is maintained in `requirements.txt`.

---

## Notes

- Dataset files and virtual environment folder (`sports-analytics-env/`) are excluded from version control via `.gitignore`
- All analysis notebooks are stored in the `notebooks/` directory

---

## Author

Jarret Angbazo