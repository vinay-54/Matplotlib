# Matplotlib Data Visualization Repository

A comprehensive collection of data visualization projects using Python's Matplotlib library, featuring analysis of sports data, statistical datasets, and various plotting techniques.

## 📊 Project Overview

This repository contains multiple data analysis and visualization projects, each demonstrating different aspects of data science and statistical visualization using Matplotlib. The projects span across sports analytics, statistical analysis, and data exploration techniques.

## 🗂️ Repository Contents

### Datasets
- **`IPL_Ball_by_Ball_2008_2022.csv`** - Comprehensive Indian Premier League cricket data spanning 14 seasons
- **`batsman_season_record.csv`** - Individual batsman performance statistics by season
- **`batter.csv`** - Batting statistics and metrics
- **`fours-sixes.csv`** - Boundary hitting statistics (fours and sixes)
- **`gayle-175.csv`** - Chris Gayle's record 175* innings data
- **`iris.csv`** - Classic iris flower dataset for classification analysis
- **`sharma-kohli.csv`** - Comparative statistics of premier batsmen
- **`vk.csv`** - Virat Kohli's performance data

### Python Scripts
- **`big-array.npy`** - NumPy array data file for large-scale computations
- **`first.ipynb`** - Jupyter notebook with initial data explorations and visualizations

## 🚀 Features

### Sports Analytics
- **Cricket Data Analysis**: Deep dive into IPL statistics, player performances, and match insights
- **Player Comparisons**: Statistical comparison between top performers
- **Performance Trends**: Season-wise analysis of batting statistics

### Statistical Visualizations
- **Distribution Analysis**: Using the classic iris dataset for pattern recognition
- **Time Series Analysis**: Trend analysis across multiple seasons
- **Comparative Studies**: Side-by-side performance metrics

### Visualization Techniques
- Line plots for trend analysis
- Bar charts for categorical comparisons
- Scatter plots for correlation studies
- Histograms for distribution analysis
- Box plots for statistical summaries

## 📋 Prerequisites

```bash
pip install matplotlib
pip install pandas
pip install numpy
pip install jupyter
```

## 🔧 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/vinay-54/Matplotlib.git
   cd Matplotlib
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook first.ipynb
   ```

## 📈 Usage Examples

### Basic Data Loading
```python
import matplotlib.pyplot as plt
import pandas as pd

# Load IPL data
ipl_data = pd.read_csv('IPL_Ball_by_Ball_2008_2022.csv')

# Create basic visualization
plt.figure(figsize=(10, 6))
plt.plot(data['season'], data['runs'])
plt.title('Runs Scored Across IPL Seasons')
plt.show()
```

### Player Performance Analysis
```python
# Load batsman data
batsman_data = pd.read_csv('batsman_season_record.csv')

# Plot season-wise performance
plt.figure(figsize=(12, 8))
plt.bar(batsman_data['season'], batsman_data['runs'])
plt.title('Batsman Performance by Season')
plt.xlabel('Season')
plt.ylabel('Runs Scored')
plt.show()
```

## 📊 Key Insights & Findings

- **IPL Trends**: Analysis reveals growth patterns in cricket scoring over 14 seasons
- **Player Metrics**: Comparative analysis of top performers in different formats
- **Statistical Patterns**: Distribution analysis using classical datasets

## 🛠️ Technologies Used

- **Python 3.x**
- **Matplotlib** - Primary visualization library
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Jupyter Notebook** - Interactive development environment

## 📁 File Structure

```
Matplotlib/
├── IPL_Ball_by_Ball_2008_2022.csv
├── batsman_season_record.csv
├── batter.csv
├── big-array.npy
├── first.ipynb
├── fours-sixes.csv
├── gayle-175.csv
├── iris.csv
├── sharma-kohli.csv
├── vk.csv
└── README.md
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📝 Future Enhancements

- [ ] Interactive visualizations using Plotly
- [ ] Machine learning predictions on sports data
- [ ] Advanced statistical analysis
- [ ] Web dashboard using Streamlit
- [ ] Real-time data integration

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

**Vinay** - [GitHub Profile](https://github.com/vinay-54)

⭐ **Don't forget to star this repository if you found it helpful!**

---

*This repository showcases the power of data visualization in uncovering insights from complex datasets, particularly in the realm of sports analytics and statistical analysis.*
