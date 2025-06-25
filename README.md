
# 🧸 Toy Data Analysis Notebook

This repository contains a simple Jupyter Notebook used for basic data analysis and experimentation, ideal for beginners learning Python, pandas, and NumPy.

## 📄 File Structure

- `toy.ipynb`: The main Jupyter Notebook file which includes:
  - File upload through Google Colab
  - Basic data manipulation using `pandas` and `numpy`
  - Placeholder cells for data processing and visualization

## 🚀 Features

- Upload your dataset in `.csv` format
- Explore the shape, head, and basic stats of your data
- Customize cells to add data cleaning, transformation, and visualizations

## 🛠 Requirements

This notebook runs in [Google Colab](https://colab.research.google.com/) and uses the following Python libraries:

```bash
numpy
pandas
```

No installation is needed if you're using Colab.

## 📦 How to Use

1. Open the notebook in Google Colab.
2. Upload your dataset via the upload cell.
3. Modify the notebook cells to suit your data analysis task.

## 📈 Sample Code Snippet

```python
import numpy as np
import pandas as pd

from google.colab import files

uploaded = files.upload()

for fn in uploaded.keys():
    print(f'User uploaded file "{fn}" with length {len(uploaded[fn])} bytes')
```

## 📚 License

This project is open-sourced under the MIT License.
