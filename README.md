# 📈 AI Methods for Portfolio Optimization in Taiwan's Stock Market: Analyzing Financial and Economic Data

## 📌 Project Overview
This project utilizes **Artificial Intelligence techniques** to optimize investment portfolios in Taiwan's stock market, focusing on the application of **Modern Portfolio Theory (MPT)**. The objective is to construct portfolios that **minimize risk** while ensuring a **minimum expected return** that surpasses the Taiwan 50 Index.

## 📂 Repository Structure
```
📂 data/  # Processed datasets used in the project
│── 📂 Status_of_TWSE/  # Market status and expected return datasets
│   ├── 201001_expected_return.csv  # TWSE stocks info & expected return in Jan 2010 as sample data
│   ├── Liquidity_Filtered_Stocks.csv  # Stocks filtered based on liquidity criteria
│   ├── MPT_algorithm_data.csv  # Preprocessed data used for MPT calculations
│   ├── Top_20_Combined_Stock_Info.csv  # Processed top 20 stocks data
│── 📂 TW50_Index/  # TW50 index sample data
│   ├── TAI50I-2010-01_edited.csv # Cleaned TW50 index data for Jan 2010
├── Stock_Categories.csv  # Categorization of stocks by industry
├── Categorized_Stock.csv  # Categorization of stocks by industry for final filtered stocks 
├── Top_20_Cov_Matrix.csv  # Covariance matrix for top 20 stocks
├── Top_20_Filtered_DataSet.csv  # Filtered dataset of the top 20 stocks
│
📂 notebooks/  # Jupyter Notebooks for analysis and optimization
│── MPT_Optimization.ipynb
│── MPT_Stock_Screening.ipynb
│── Monte_Carlo_Simulation.ipynb
│── Stock Classification.ipynb
│── Stock_Price_Final.ipynb
│── TW50_Index_Data_Clean.ipynb
│
📂 results/  # Final results and visualizations
│── 📂 Portfolio_Allocation/  # Industry and stock allocation charts
│   ├── bar_chart_portfolio_allocation_by_industry.png
│   ├── bar_chart_top_20_portfolio_allocation_by_industry.png
│   ├── pie_chart_portfolio_allocation_by_industry.png
│   ├── pie_chart_top_20_portfolio_weight_allocation.png
│
│── 📂 Simulation_Results/  # Monte Carlo simulation results
│   ├── Simulated_Portfolio_Annualized_Returns_Distribution.png
│   ├── Top_20_Simulated_Portfolio_Annualized_Returns_Distribution.png
│
│── 📂 Stock_Weights/  # Stock weight distribution charts
│   ├── bar_chart_top_20_stocks_weights.png
│   ├── bar_chart_top_20_weight_distribution_portfolio_stocks.png
│   ├── optimised_weights.csv
│   ├── top_20_optimised_weights.csv
│
📂 reports/  # Project report and appendix
│── Final_Report.pdf
│── Appendix.pdf
│
📂 presentation/  # Project presentation slides
│── Presentation-PRJ.pdf
│
📄 README.md  # Project documentation
📄 LICENSE  # License information
📄 .gitignore  # Files ignored in version control
```
## 📊 Data Sources & How to Obtain
The datasets used in this project originate from publicly available financial sources. The data processing pipeline cleans and structures the data for analysis.

- **Stock Market Data & Economic Indicators:** Collected from [Taiwan Stock Exchange (TWSE)](https://www.twse.com.tw/zh/index.html)
- **Taiwan 50 Index (TW50) Data:** Retrieved from [FTSE TWSE Taiwan 50 Index Historical Data](https://www.twse.com.tw/zh/indices/ftse/tai50i.html)


## 📑 Files Description
### 📄 **Final Report** ([Final_Report.pdf](reports/Final_Report.pdf))
The final report encompasses the comprehensive findings from the research, detailing the **methodology, analysis, and results** of the portfolio optimization processes. It covers:
- **Theoretical Background** (Modern Portfolio Theory, Monte Carlo Simulations)
- **Data Collection & Cleaning**
- **Portfolio Optimization using MPT**
- **Evaluation of Optimized Portfolios**

### 📘 **Jupyter Notebooks**
These Jupyter notebooks contain the code and computational experiments used in the research. Each notebook focuses on a specific part of the project:

- `Stock_Price_Final.ipynb` → **Processes and finalizes stock price data**
- `TW50_Index_Data_Clean.ipynb` → **Cleans and preprocesses Taiwan 50 Index data**
- `MPT_Stock_Screening.ipynb` → **Filters stocks based on liquidity & expected returns**
- `MPT_Optimization.ipynb` → **Applies MPT to optimize the portfolio**
- `Stock_Classification.ipynb` → **Classifies stocks by industry & characteristics**
- `Monte_Carlo_Simulation.ipynb` → **Simulates portfolio risk & returns under different scenarios**

### 📊 **Results & Visualizations**
#### **Portfolio Allocation**
- **Industry Allocation:** [Portfolio by Industry](results/Portfolio_Allocation/bar_chart_portfolio_allocation_by_industry.png)
- **Top 20 Stocks Allocation:** [Top 20 Portfolio](results/Stock_Weights/bar_chart_top_20_stocks_weights.png)

#### **Risk & Return Simulation**
- **Monte Carlo Simulation:** [Return Distribution](results/Simulation_Results/Simulated_Portfolio_Annualized_Returns_Distribution.png)
- **Top 20 Portfolio Performance:** [Simulated Top 20](results/Simulation_Results/Top_20_Simulated_Portfolio_Annualized_Returns_Distribution.png)

## 🎤 **Presentation & Reports**
📄 [Project Presentation (PDF)](presentation/Presentation-PRJ.pdf)  
📄 [Final Report (PDF)](reports/Final_Report.pdf)  
📄 [Appendix (PDF)](reports/Appendix.pdf)  

## 📝 License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

## 🤝 Contributors
- **Chun-I Chien** - *Lead Developer & Researcher*
- **Supervised by:** Prof. Peter McBurney  
- **Programme of Study:** BSc Computer Science, King's College London  



