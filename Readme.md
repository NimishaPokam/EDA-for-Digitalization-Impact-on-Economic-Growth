## Project Overview  
This project investigates the impact of digitalization on economic growth using a Cobb-Douglas production function framework. Economic growth, the dependent variable, is measured as GDP per capita in constant 2015 US dollars. The study incorporates digitalization indicators and macroeconomic control variables to analyze their relationship and influence on economic performance.  
The dataset used for this analysis is sourced from [Mendeley Data](https://data.mendeley.com/datasets/ctm7vvpp7n/1)

---

## Digitalization Indicators  
The following metrics represent digitalization in this study:  
1. **Fixed Telephone Subscriptions** (per 100 people)  
2. **Mobile Cellular Subscriptions** (per 100 people)  
3. **Broadband Subscriptions** (per 100 people)  
4. **Individuals Using the Internet** (% of population)  
5. **Digitalization Development Level** (composite index derived using PCA)  

---

## Macroeconomic Control Variables  
To capture the broader economic context, the following variables are included:  
1. **Investment**: Gross fixed capital formation (% of GDP)  
2. **Trade Openness**: Sum of imports and exports (% of GDP)  
3. **Labor Force**: Total labor force participation rate  
4. **Inflation**: Consumer price index (%)  
5. **Population**  
6. **Government Consumption**: Expenditure on goods and services (% of GDP)  
7. **R&D Expenditure**  

---

## Additional Metadata  
- Countries are classified by income level (High, Medium, Low) as per World Bank classifications.  
- The dataset covers multiple continents, countries, and income categories.  
- To manage skewness, all data is transformed into logarithmic form.  

Digitalization is measured using fixed telephone subscriptions, mobile cellular subscriptions, internet usage, and broadband subscriptions. A composite index summarizes digitalization levels, while macroeconomic variables account for constraints like investment, trade openness, labor force dynamics, and government consumption.

---

## Project Workflow  

### 1. **Libraries Used**  
The following Python libraries were leveraged for data handling and visualization:  
- **Pandas**: For data manipulation, including handling missing values and renaming columns.  
- **NumPy**: For numerical computations and data transformation.  
- **Matplotlib**: For creating static, publication-quality charts such as line graphs and bar plots.  
- **Seaborn**: For detailed and aesthetically pleasing visualizations, including correlation matrices and distribution plots.  

### 2. **Data Cleaning**  
Key cleaning steps included:  
- Dropping redundant columns.  
- Renaming columns for clarity.  
- Imputing missing values with appropriate methods.  

### 3. **Summary Statistics**  
Summary statistics provided insights into key measures such as central tendency (mean, median) and variability (range, standard deviation), offering a concise overview of the dataset.  

### 4. **Distribution Analysis**  
Distribution analysis visualized data patterns, outliers, and skewness, guiding transformation and further analysis.  

### 5. **Correlation Matrix**  
A correlation matrix explored relationships between:  
- Digitalization indicators  
- Macroeconomic control variables  

The analysis revealed strong interrelationships among digitalization metrics, such as internet usage and broadband subscriptions, while highlighting weaker links with labor-intensive metrics. Wealthier nations showed higher investments in digital infrastructure and R&D, driving innovation and growth.  

### 6. **Regional Comparisons**  
#### a. **Internet Usage by Continent**  
Internet adoption trends were compared across continents, revealing disparities:  
- Europe led in internet adoption.  
- Africa exhibited rapid growth despite remaining the least connected region.  

#### b. **Investment and Trade Openness by Continent**  
Analyzed regional economic policies and their impacts:  
- **Trade Openness**: Europe consistently led, driven by strong intra-continental trade, with declines post-2015 reflecting global economic challenges.  
- **Investment**: Arab States led in infrastructure investments, while Africa and the Americas lagged due to resource and industrialization constraints.  

### 7. **Visualizations: Top 10 and Bottom 10 Countries**  
#### a. **Digitalization Indicators**  
Top-performing countries excelled in broadband and internet usage, while the bottom 10 faced challenges in infrastructure and access.  

#### b. **Macroeconomic Variables**  
Countries with high trade openness and investment showed better economic growth, while those with low levels reflected economic constraints.  

Developed nations demonstrated stronger digital and economic metrics due to robust infrastructure and R&D investment. Conversely, developing countries struggled with low internet penetration and limited resources.  

---

## Conclusion  
This project highlights the strong relationship between digitalization and economic growth, emphasizing the role of infrastructure, internet accessibility, and economic policies in fostering development. The findings underscore the need for targeted policies to bridge digital and economic divides, offering actionable insights for policymakers.  

For further inquiries or reproducibility, refer to the original dataset linked above.  
