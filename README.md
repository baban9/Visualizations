# Data Visualizations

Exploratory data analysis notebooks demonstrating Matplotlib, Seaborn, Bokeh, heatmaps, pair plots, and image analysis patterns.

## Problem

Communicate data distributions, relationships, and image-derived features through consistent visualization choices.

## Notebook index

| Notebook | Library | Focus |
|----------|---------|-------|
| Data Visualization - Matplotlib !!.ipynb | Matplotlib | Base plotting |
| Data Visualization - Seaborn !!.ipynb | Seaborn | Statistical plots |
| Data Visualization - Heatmap !!.ipynb | Seaborn/Matplotlib | Correlation heatmaps |
| Data Visualization - Pair Plots !!.ipynb | Seaborn | Multivariate relationships |
| Data Visualization - Bokeh !!.ipynb | Bokeh | Interactive charts |
| Image Analysis !!.ipynb | OpenCV/Matplotlib | Image EDA |

## Reproducibility

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

## Tech stack

Python 3, Matplotlib, Seaborn, Bokeh, Jupyter

## Limitations and next steps

- Standardize notebook naming (remove `!!` suffixes)
- Add a shared `viz_theme.py` for consistent color palettes
- Export key charts as PNG for portfolio case studies
