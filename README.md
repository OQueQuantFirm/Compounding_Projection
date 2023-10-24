## Analytical Report: Compounding and Trading Analysis

The provided code and CSV output represent a compounding and trading analysis over a 30-day period. The analysis involves simulated trading of a portfolio with an initial capital of $20,000. Each day, a portion of the portfolio is allocated to a trade, and the outcome (win or loss) and resulting profit/loss are recorded. The new portfolio value is then calculated for each day.

### Cumulative Portfolio Growth:
The cumulative portfolio growth over the 30-day period shows a steady increase, highlighting the effectiveness of the compounding strategy. The initial capital of $20,000 has grown to $33,665.90, resulting in a total return of approximately 68.33%.

<img width="942" alt="Screenshot 2023-10-24 at 10 28 11" src="https://github.com/OQueQuantFirm/Compounding_Projection/assets/147313218/230d233a-b47b-4734-a9c3-1e9b89224181">

### Portfolio value over time

The daily portfolio values provide a detailed view of the portfolio's performance. The strategy involves a mix of winning and losing trades, resulting in fluctuations in the portfolio value. Notably, winning trades contribute positively to portfolio growth, while losing trades lead to temporary drawdowns.

<img width="980" alt="Screenshot 2023-10-24 at 10 28 56" src="https://github.com/OQueQuantFirm/Compounding_Projection/assets/147313218/9a2a5e5d-e54b-4f00-ad61-e3b1f6a73ba2">

Dailiy Return Historgam
<img width="972" alt="Screenshot 2023-10-24 at 10 29 25" src="https://github.com/OQueQuantFirm/Compounding_Projection/assets/147313218/30dcdc20-efe1-4b3b-a8ae-d32a015a4479">

### Trading Signals:
The trading signals, categorized as "Win" or "Loss," are based on a predetermined strategy. The strategy employs a stop loss of 10% and a take profit of 15%, with an 80% win rate and a 20% loss rate.

Performance Metrics:
Total Return: 68.33%

The total return represents the percentage increase in portfolio value over the 30-day period.
Max Drawdown: -1.51%

The max drawdown measures the maximum loss from a peak to a trough during the trading period.
Sharpe Ratio: 77,705.3

The Sharpe ratio assesses the risk-adjusted return of the portfolio. A higher Sharpe ratio indicates a better risk-adjusted performance.

The compounding and trading analysis demonstrate a successful strategy, resulting in significant portfolio growth over the 30-day period. The use of a well-defined trading strategy, coupled with effective risk management, has contributed to the overall positive performance. However, it's essential to note that past performance is not indicative of future results, and market conditions may vary.

This analysis can serve as a foundation for further refinement of trading strategies and risk management techniques. 

### Installation Guide for Windows:

1. **Clone the Repository:**

   Open the command prompt and run the following command:

   ```bash
   git clone https://github.com/OQueQuantFirm/Compounding_Projection.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd Compounding_Projection
   ```

3. **Install Jupyter Notebook:**

   If you don't have Jupyter Notebook installed, you can install it using:

   ```bash
   pip install jupyter
   ```

4. **Install Required Libraries:**

   Your code uses Plotly and Pandas. Install them using:

   ```bash
   pip install plotly pandas
   ```

   Ensure that you are in the project directory before running this command.

### Usage Guide:

1. **Open Jupyter Notebook:**

   In the command prompt, run:

   ```bash
   jupyter notebook
   ```

   This will open Jupyter Notebook in your default web browser.

2. **Open the Jupyter Notebook File:**

   Navigate to the project directory in the Jupyter Notebook interface and open the `Compounded Projection.ipynb` file.

3. **Run the Code:**

   Inside the Jupyter Notebook, run each cell of the notebook sequentially.

### Compounding Analysis:

   - The compounding analysis is automatically performed as part of the notebook. The cumulative returns plot will be displayed.

### Trading Analysis:

   - The trading analysis is also included in the notebook. The trading signals and performance metrics will be printed and visualized.

### Additional Notes:

   - If you encounter any issues, ensure that your Python environment is correctly set up and that all dependencies are installed.

   - Make sure to have an active internet connection, as Plotly may need to download additional resources the first time you run the code.

   - If you face any issues with dependencies, you can install them using the `pip install` command.

That's it! Users should be able to clone the repository, install the required libraries, and run the Jupyter Notebook on their Windows system. Adjustments can be made to this guide based on specific user feedback or updates to the project.
