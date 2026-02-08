# 📊 Seaborn Data Visualization Practice

A beginner-friendly guide to data visualization with **Seaborn**, built as a learning project for GitHub practice.

## 🎯 What is This Project?

This is a practice project exploring **Seaborn**, a powerful Python visualization library. It contains hands-on examples of different plot types and demonstrates how to create beautiful, insightful visualizations from data.

> **Note:** This is a learning/practice project, not a production-ready library. Feel free to use it to learn or as inspiration for your own projects!

## 📚 Project Structure

```
07_Seaborn/
├── README.md                          # This file
├── seaborn_intro.ipynb               # Introduction to Seaborn basics
└── seaborn_plots.ipynb              # Practical examples with different plot types
```

## 📖 Notebooks Overview

### 1. **seaborn_intro.ipynb** - Getting Started

- Introduction to Seaborn and why it's useful
- Basic setup and imports
- Creating your first simple line plot
- Exploring different theme styles

**Learn:**

- How Seaborn compares to Matplotlib
- Basic plotting syntax
- Customizing plots with titles, labels, and markers

### 2. **seaborn_plots.ipynb** - Visualization Examples

Practical examples with real datasets:

#### **Tips Dataset Examples**

- **Line Plot** - Showing relationships between continuous variables
- **Scatter Plot** - Individual data point visualization
- **Bar Plot** - Categorical comparisons
- **Box Plot** - Distribution and outlier detection

#### **Flights Dataset Examples**

- **Heatmap** - Visualizing patterns across two categorical variables
- Demonstrates data pivoting for heatmap preparation

#### **Custom Data Examples**

- **Scatter Plot with Hue** - Adding a third dimension using color
- Multi-variable visualization techniques

## 🚀 Getting Started

### Prerequisites

```bash
Python 3.7+
```

### Installation

```bash
# Install required packages
pip install seaborn matplotlib pandas numpy
```

### Running the Notebooks

1. **Clone or download this repository**
2. **Open with Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
3. **Navigate to the notebooks and click to open**
4. **Run cells sequentially** (Ctrl + Enter to run a cell)

Or use **VS Code with Jupyter extension** for a modern experience.

## 📊 Plot Types Covered

| Plot Type        | Use Case                          | Example                  |
| ---------------- | --------------------------------- | ------------------------ |
| **Line Plot**    | Trend over time                   | Total Bill vs Tip        |
| **Scatter Plot** | Individual points & relationships | Salary vs Age            |
| **Bar Plot**     | Categorical comparisons           | Average by Category      |
| **Box Plot**     | Distribution & outliers           | Bills by Day             |
| **Heatmap**      | 2D categorical patterns           | Passengers by Month/Year |

## 🎨 Key Seaborn Features Demonstrated

✅ **Built-in Datasets** - Using `sns.load_dataset()`  
✅ **High-level API** - Clean, concise code  
✅ **Themes & Styling** - Professional-looking plots with minimal effort  
✅ **Color Palettes** - Beautiful color schemes (`Set1`, `viridis`, etc.)  
✅ **DataFrame Integration** - Direct pandas DataFrame support  
✅ **Customization** - Titles, labels, legends, and more

## 💡 Tips for Learning

1. **Run each cell individually** to see output step-by-step
2. **Modify the code** - Change colors, datasets, or parameters
3. **Experiment with palettes** - Try different color schemes
4. **Practice customization** - Add more titles, labels, and styling
5. **Create your own plots** with your own data!

## 🔗 Useful Resources

- [Seaborn Official Documentation](https://seaborn.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Seaborn Tutorial GitHub](https://github.com/mwaskom/seaborn)

## 📝 What You'll Learn

After working through these notebooks, you'll understand:

- The difference between Matplotlib and Seaborn
- How to load and explore built-in datasets
- Creating different types of visualizations
- Customizing colors, themes, and labels
- Working with DataFrames for visualization
- Using categorical encoding with colors (hue)
- Data pivoting for heatmaps
- Best practices for readable, beautiful plots

## 🎓 Next Steps for Practice

Once you've gone through the examples:

1. **Load your own data** and create visualizations
2. **Combine multiple plots** using `plt.subplots()`
3. **Explore advanced plots** like violin plots, KDE plots, pair plots
4. **Create dashboards** combining multiple visualizations
5. **Experiment with themes** - `sns.set_theme(style="...")`

## 🐛 Issues & Suggestions

Found a bug or have suggestions? Feel free to:

- Open an issue on GitHub
- Submit a pull request with improvements
- Create your own fork and experiment

## 📄 License

This is a practice/learning project. Feel free to use, modify, and learn from it!

---

**Happy Learning! 🚀**

_Created as a practice project for learning data visualization with Seaborn._
