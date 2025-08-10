# Food Delivery Cost and Profitability Analysis

This project analyzes a simulated food delivery dataset to understand the company's financial performance. The core goal is to identify why the company is currently unprofitable and to simulate a new pricing strategy (commission and discount rates) that could lead to profitability.

## 📁 Files

- `food_delivery_cost_and_profitability_Analysis.ipynb`: The main Jupyter Notebook that contains the full data analysis, visualizations, and simulation.
- `set2.csv`: The dataset used in this analysis (assumed to be in the same directory as the notebook).

## 🚀 Key Analysis & Findings

The analysis is structured to first understand the current financial health and then propose a data-driven solution.

### 📊 Current Financial Situation

By calculating total revenue, costs, and profit, the analysis reveals that the company is **currently operating at a significant loss**.

| Metric | Amount (INR) |
| :--- | :--- |
| **Total Revenue** | 126,990 |
| **Total Costs** | 221,741.85 |
| **Total Profit** | -117,943.85 |

A breakdown of the costs shows that **discounts and offers** are the primary drivers of unprofitability, followed by delivery and payment processing fees.

### 💡 Proposed Solution: A New Pricing Strategy

To address the losses, the notebook isolates the subset of orders that were **profitable** under the current model. By analyzing the average commission and discount rates for just these profitable orders, a new, more sustainable pricing strategy is recommended:

- **Recommended Commission Percentage**: 37.0%
- **Recommended Discount Percentage**: 10.0%

### 📈 Simulation Results

The notebook simulates the company's profitability using these new, recommended rates. The results show a significant improvement:

| Metric | Amount (INR) |
| :--- | :--- |
| **Simulated Total Costs** | 163,848.90 |
| **Simulated Total Profit** | 226,119.63 |

The simulation demonstrates that adopting this new strategy could shift the company from being unprofitable to being highly profitable. The final visualization compares the distribution of profits before and after the simulation, clearly illustrating the positive impact.

## 🛠️ How to Run the Notebook

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/food-delivery-analysis.git](https://github.com/your-username/food-delivery-analysis.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd food-delivery-analysis
    ```
3.  **Ensure you have the necessary libraries installed** (pandas, numpy, matplotlib, seaborn). If not, you can install them via pip:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
4.  **Place your `set2.csv` file** in the same directory.
5.  **Start a Jupyter Notebook server:**
    ```bash
    jupyter notebook
    ```
6.  Open and run the `food_delivery_cost_and_profitability_Analysis.ipynb` notebook to see the analysis in action.
