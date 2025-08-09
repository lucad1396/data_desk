# 📊 Data Desk

A collection of simple, practical guides on working with data in Python - from data wrangling with **Pandas** to creating insightful visuals with **Seaborn** and other libraries.

This repository is meant as a personal reference and learning tool, but also as a resource for others who want clear, example-driven introductions to essential tools in the data science workflow.

## 📁 Contents

- `pandas_guide.ipynb` - Step-by-step guide to data manipulation with **Pandas**, covering:

  - 🧱 **Data structures**: DataFrames, Series, and indexing
  - 📥 **Data input & inspection**: Reading, inspecting & cleaning data
  - 📊 **Grouping & summarizing**: Sorting, grouping, and computing summary statistics
  - ❓ **Missing data**: Handling missing values and duplicates
  - 🔄 **Transformation**: Using `map`, `apply`, `replace`
  - 🛠️ **Feature engineering & preprocessing**: Creating and refining features to improve analysis or modeling
  - 🔗 **Combining data**: Merging, joining & concatenating datasets
  - 🚀 **Performance tips**: Working with large datasets efficiently

- `seaborn_guide.ipynb` - A structured guide to data visualization with **Seaborn**, organized by use case:

  - 📈 **Trends**: Line plots for visualizing change over time (`lineplot`)
  - 📊 **Relationships**: Explore connections between variables using bar plots, heatmaps, scatter plots, regression plots (`barplot`, `heatmap`, `scatterplot`, `regplot`, `lmplot`, `swarmplot`)
  - 📉 **Distributions**: Understand variable distributions with histograms, KDEs, jointplots, displots, and more (`histplot`, `kdeplot`, `jointplot`, `displot`, `DataFrame.hist`)
  - 🔁 **Faceting & Grouped Plots**: Visualize subgroups with `FacetGrid`, `lmplot(col=...)`, and grouped bars
  - 📊 **Multivariate Patterns**: Summary overviews using `pairplot` and `countplot`
  - 🧰 Tips on normalization, log scales, and figure-level vs axes-level plots

- `plotly_guide.ipynb` – An introduction to interactive data visualization with Plotly Express:
  - ⚡ Create interactive plots quickly with `plotly.express`
  - 🎯 Understand and choose the right Plotly renderer
  - ⏱️ Explore line charts, animated bar and scatter plots for time series data
  - 🧩 Use faceting for small multiples and richer insights
  - 🎨 Customize colors, markers, layouts, and axes
  - 💾 Export figures as HTML or static images
  - 🌍 Real-world example: Canadian gasoline prices over time
  - 📌 General tips for working with Plotly Express

- `datasets/` - Contains small datasets used in the notebooks (e.g. CSVs from seaborn, open datasets).

## 🚀 Why This Exists

This repository helps reinforce best practices in handling and visualizing data. It’s designed to be:
- **Practical**: Minimal theory, lots of examples.
- **Readable**: Clean notebooks, commented code.
- **Re-usable**: A toolkit for real projects and interviews.

## 🛠️ Tools & Libraries

- Python 3.x
- Pandas
- Seaborn
- Matplotlib
- NumPy

## 📌 Next Steps

This repo is part of a broader effort to transition into industry roles in data science and machine learning. Upcoming companion repos:
- `ml_desk/`: Guides on regression, classification, model evaluation, and ML workflows.
- `projects/`: End-to-end case studies applying these tools to real-world datasets.

---

Feel free to clone, fork, or suggest improvements!