# 🌍 Midterm Project - Visualizing Economic Indicators Across Countries

### 👥 Authors: F74121157 & F74121149  
### 📄 Presentation: [`14_F74121157_F74121149_presentation1.pdf`](./14_F74121157_F74121149_presentation1.pdf)

---

## 📌 Project Title

**"Understanding the Relationship Between GDP, GNI, Unemployment, and Government Debt Across Nations"**

---

## 🎯 Project Goal

This project aims to integrate multiple international economic indicators to visually explore the following questions:

- Do high-income and low-income countries exhibit similar government debt structures?
- Does GNI more accurately reflect a country's economic strength compared to GDP?
- Which countries maintain high government debt despite having high GDP per capita?
- Is government debt significantly correlated with unemployment rates?

---

## 📁 Repository Structure

```
.
├── README.md                            # This documentation
├── assignment4.ipynb                    # Main analysis and visualization notebook
├── data/                                # Original datasets
│   ├── GDP/                             # GDP (total)
│   ├── GDP_per/                         # GDP per capita
│   ├── GNI/                             # GNI per capita
│   ├── debt/                            # Government debt (% of GDP)
│   ├── inflation/                       # Inflation data
│   ├── interest/                        # Interest rate data
│   ├── population/                      # Total population
│   ├── tax_revenue/                     # Tax revenue (% of GDP)
│   ├── unemploy/                        # Unemployment rate
│   ├── import_export/, metro/, air_pollution/ # Additional Taiwan local data (unused in this analysis)
├── result/                              # Output images
│   ├── 1.jpg ~ 4.jpg                    # Visualization outputs
│   └── diagram.PNG                      # Summary or process diagram
└── 14_F74121157_F74121149_presentation1.pdf
```

---

## 📊 Data Sources & Descriptions

| Indicator                 | Description                                      | Data Source                                                     |
|---------------------------|--------------------------------------------------|-----------------------------------------------------------------|
| **GDP per capita**        | Gross Domestic Product per capita                | [World Bank - GDP per Capita](https://data.worldbank.org/indicator/NY.GDP.PCAP.CD) |
| **GNI per capita**        | Gross National Income per capita                 | [World Bank - GNI per Capita](https://data.worldbank.org/indicator/NY.GNP.PCAP.CD) |
| **Government Debt (% GDP)**| Government debt as a percentage of GDP          | [IMF Global Debt Database](https://www.imf.org/external/datamapper/datasets/GDD)   |
| **Unemployment Rate**     | Percentage of labor force unemployed             | [World Bank - Unemployment](https://data.worldbank.org/indicator/SL.UEM.TOTL.ZS)   |
| **Population**            | Total population count                           | [World Bank - Population](https://data.worldbank.org/indicator/SP.POP.TOTL)        |

**📅 All data correspond to the year 2023.**

---

## 🧪 How to Run

1. **Clone the repository and navigate to the folder:**

```bash
git clone <your-repo-url>
cd <your-repo-folder>
```

2. **Install dependencies:**

```bash
pip install pandas matplotlib seaborn
```

3. **Open and run `assignment4.ipynb`:**

- Open with Jupyter Notebook or VSCode
- Run each cell sequentially to generate visual outputs in the `result/` directory

---

## 📈 Key Visual Outputs

- **Bubble Chart:** Comparing GDP vs. Debt (colored by GNI, sized by population)
- **Country Labels and Groupings:** Segmentation by income level
- **Trend Identification:** Insights into different country clusters

---

## 📌 Notes

- Some data files retain their original World Bank filenames. Verify data loading logic carefully in `assignment4.ipynb`.
- To update data for future years, replace corresponding CSV files in the `data/` folder.

---

## 📬 Contact

For any questions or suggestions about this project, please contact us:

- **F74121157**
- **F74121149**

