# 🛒 Olist E-Commerce Data Analysis (SQL & Python)

This project analyzes over 100,000 real orders from **Olist**, a large e-commerce marketplace in Brazil. 

The goal of this analysis is to help the business understand sales, customer habits, and product combinations.

---

## 📌 Main Questions & Findings

| Question | What We Found | Business Action |
| :--- | :--- | :--- |
| **Top Categories** | `health_beauty`, `watches_gifts`, and `bed_bath_table` make over 50% of all sales. | Spend more ad budget on these categories. |
| **City Sales & AOV** | `Sao Paulo` has the most orders, but `Brasilia` and `Goiania` spend more money per order (higher AOV). | Target higher-priced items to Brasilia and Goiania. |
| **Peak Hours** | Orders peak between **10:00 AM and 04:00 PM**. | Send marketing emails and flash sales around midday. |
| **Cross-Selling** | `bed_bath_table` and `furniture_decor` are the most popular pair bought together. | Create bundle discounts for these two categories. |

---

## 🛠️ Tools Used
- **SQL (SQLite):** To filter, join, and group tables in memory.
- **Python:** `pandas` and `numpy` for data handling.
- **Charts:** `matplotlib`, `seaborn`, and `squarify` (Treemap).
- **Dataset:** [Brazilian E-Commerce Public Dataset by Olist on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

## 📂 Project Structure

```text
├── olistd/                        # Raw CSV data files
├── olist_ecommerce_analysis.ipynb # Main analysis notebook (SQL + Python)
├── README.md                      # Project summary
└── requirements.txt               # Required Python packages
```

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone [https://github.com/your_username/olist-ecommerce-analytics.git](https://github.com/your_username/olist-ecommerce-analytics.git)
cd olist-ecommerce-analytics
```

2. Install the libraries:
```bash
pip install -r requirements.txt
```

3. Open the notebook:
```bash
jupyter notebook olist_ecommerce_analysis.ipynb
```
