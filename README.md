# Stock Portfolio Optimization and Rebalancing Analysis

This project combines Modern Portfolio Theory (MPT), integer programming, and Monte Carlo simulation to optimize stock investments and analyze different rebalancing strategies.

## Project Overview
This project aims to create and evaluate a data-driven approach to stock portfolio management. By leveraging mathematical and simulation techniques, we seek to understand the interplay between risk, return, and rebalancing strategies in the context of financial investment. This is based on work for a university class and highlights application of financial modeling techniques.

## How this Project Came About
This project was created as part of an academic effort to explore advanced quantitative finance techniques. We were interested in the ability to practically apply Modern Portfolio Theory and Monte Carlo Simulation to develop a realistic and actionable investment strategy. The project was initiated to develop and test a practical stock investment plan using these analytical tools.

## Motivation
Our primary motivation was to create a model that would take a holistic approach to investment optimization. By combining Modern Portfolio Theory with integer programming and Monte Carlo simulation, our goal was to provide a model that not only selects a range of well-balanced allocations, but also simulates real-world market conditions and rebalancing strategies.

## Key Features

*   **Data Preparation:** Retrieval of real-world stock data and identification of high-performing stocks per sector. Data was analyzed and organized to best perform analysis.
   ![Normalized performance of top stocks per sector (2017–2022).](https://github.com/user-attachments/assets/bf9ea2d5-8fe3-4bd2-b505-c1a36c33c903)

*   **Modern Portfolio Theory (MPT):** Implementation of MPT to optimize portfolio allocation for various risk levels, utilizing integer programming for realistic stock selection and allocation.
   ![Efficient Frontier showing optimal portfolios for different risk levels.](https://github.com/user-attachments/assets/7ec80fc7-61c7-47f6-9f13-83cd21ad86b5)

*   **Investment Strategies:** Simulation of Buy-and-Hold, Daily Rebalance, Weekly Rebalance, and Monthly Rebalance strategies to analyze the effect of different rebalancing frequencies on portfolio returns.
    ![Portfolio value over time for Buy-and-Hold vs. rebalancing strategies.](https://github.com/user-attachments/assets/438a8930-e498-42f3-906e-0e3a00877e1e)

*   **Monte Carlo Simulation:** Use of Monte Carlo simulations to evaluate the portfolio, generate a distribution of returns and determine the probability of loss in a live market scenario.
   ![Density plot of portfolio returns with fitted normal distribution.](https://github.com/user-attachments/assets/4fb20bc2-4e9b-4d44-beb9-2a351ebca157)



## Files

*   python notebook `BDM_final.ipynb`

## Technologies Used

*   Python (for data manipulation, MPT optimization, and Monte Carlo simulation)
*   Libraries: Pandas, NumPy, Matplotlib, SciPy, Statsmodels, Pyomo
* The Pyomo library was used to set up integer programming optimization.

## Intended Use
The developed financial model can be used as a guide for investors looking to optimize their portfolios through both diversification and active management using rebalancing. It provides an analysis of different types of portfolios and helps investors to understand how different rebalancing strategies influence risk and returns over time. It also acts as an educational tool for learning about different financial techniques for investment.

## Limitations

*   **Historical Data Limitations:** The accuracy of the Monte Carlo simulation and rebalancing strategies is limited by the use of historical data which might not capture potential future market changes.
*   **Transaction Costs:** The rebalancing strategies analysis is only based on a transaction cost of 0.1% and may not capture actual cost fluctuations within the market.
*   **Model Assumptions:** The MPT model assumes that stock returns follow a normal distribution, which may not always hold true in real-world markets.
*   **Tax and Fee Considerations**: The models do not account for real-world factors such as taxes and fund management fees.

## Challenges

*   **Complex Optimization:** Implementing integer programming for MPT was challenging and required a strong understanding of optimization theory.
*   **Efficient Simulation:** Creating a large number of Monte Carlo simulations efficiently required a great deal of computing power and a strong understanding of the required parameters.
*  **Data Consistency and Organization:** Data needed to be organized and cleaned to be able to used with optimization algorithms.

## How to Use

1.  Clone this repository.
2.  Open the Python notebook, `BDM_final.ipynb`.
3.  Run the code cells sequentially to see the process, data analysis, and models.

## Notes
The data analysis and modeling was conducted via python code utilizing several libraries such as Pandas, NumPy, Matplotlib, SciPy, Statsmodels, Pyomo. The raw dataset files are not provided due to it being collected via a web scraping method. Links in the notebook will direct you to the sources where the data can be obtained.
