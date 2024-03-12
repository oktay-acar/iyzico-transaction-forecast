# Transaction Volume Forecasting using [iyzico](https://www.iyzico.com/)'s Dataset

**Business Problem**

**Iyzico** is a financial technology company that facilitates the online shopping experience for both buyers and sellers. It provides payment infrastructure for e-commerce companies, marketplaces, and individual users. A forecast is expected to be made for the total transaction volume on a **'merchant_id'** and day basis for the last 3 months of the year 2020.

**Dataset Story**

The data includes information from 7 member businesses in 7 categories from 2018 to 2021.

5 Variables, 7667 Observations, 612 KB

**Variables**
- **transaction_date:** Date of sales data
- **merchant_id:** IDs of member businesses *(Unique number for each member business)*
- **Total_Transaction:** Number of transactions
- **Total_Paid:** Payment amount

---

## Requirements
~~~python
lightgbm==3.3.5
matplotlib==3.7.1
numpy==1.24.3
pandas==1.5.1
seaborn==0.12.1
~~~

---

## Author
[Oktay Acar](https://github.com/oktay-acar)