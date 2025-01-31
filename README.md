# Big Data Analytics Kimia Farma X Rakamin Academy Batch January 2025 

## About  
The Project-Based Internship Program, a collaboration between Rakamin Academy and Kimia Farma Big Data Analytics, is a self-development and career acceleration program designed for individuals interested in exploring the Big Data Anlytics role at Kimia Farma. 

As a Big Data Analytics Intern at Kimia Farma, I will be faced with a series of challenges that require a deep understanding of data and analytical skills. One of my main projects will be to evaluate Kimia Farma's business performance from 2020 to 2023

## Task 
Here are the tasks I need to complete 
1. Importing Dataset to BigQuery
   In this project, I am tasked with importing the provided datasets and I need to import these four datasets into BigQuery as tables, with the names being the same as the dataset names but without the ".csv" extention,
   - kf_final_transaction.csv
   - kf_inventory.csv
   - kf_kantor_cabang.csv
   - kf_product.csv
2. Create an Analysis Table
   In this project, I am required to create an analysis table based on the aggregated results from the four imported tables. The table must include the following mandatory column and challenges :
   - transaction_id : transaction ID code
   - date : transaction date
   - branch_id : Kimia Farma branch ID code
   - branch_name : Kimia Farma branch name
   - kota : city where the Kimia Farma branch is located
   - provinsi : province where the Kimia Farma branch is located
   - rating_cabang : customer rating of the Kimia Farma branch
   - customer_name : name of the customer who made the transaction
   - product_id : product ID code of the medicine
   - product_name : name of the medicine
   - actual_price : price of the medicine
   - discount_percentage : discount percentage applied to the medicine
   - persentase_gross_laba : gross profit percentage that should be received from the medicine
   - nett_sales : price after dicsount
   - nett_profit : profit earned by Kimia Farma
   - rating_transaksi : customer rating of the transaction
     
3. Create Dashboard Performance Analytics Kimia Farma Business Year 2020-2023
   In this project, I am required to create a performance analysis dashboard for Kimia Farma for the years 2020-2023 using Google Looker Studio. This dashboard will be bult based on the analysis table previously created in BigQuery, so I need to connect the table to Google Looker Studio. The dashboard design can be customized based on my creativity, but it must included
   - Dashboard Title
   - Dashboard Summary
   - Filter Control
   - Snapshot Data
   - Year over Year Revenue Comparison for Kimia Farma
   - Top 10 Branches by Total Transaction (Province Level)
   - Top 10 Branches by Nett Sales (Province Level)
   - Top 5 Branches with the Highest Ratings but the Lowest Transaction Ratings
   - Indonesia's Geo Map Showing Total Profit by Province
   - Additional analyses that can be further explored
     
## Create Data Analytics in Big Query
Using four CSV files from the dataset, the data was imported into Google BigQuery for further processing.
### Overview of Dataset
- kf_product
  <img width="916" alt="image" src="https://github.com/user-attachments/assets/b979ced4-d658-4533-9308-8bd973e3423b" />
- kf_kantor_cabang
  <img width="914" alt="image" src="https://github.com/user-attachments/assets/e5705581-95eb-4141-9677-a11177938fc7" />
- kf_inventory
  <img width="914" alt="image" src="https://github.com/user-attachments/assets/e1a29b6a-e00f-4c78-a680-9bae2b4fe2a4" />
- kf_final_transaction
  <img width="996" alt="image" src="https://github.com/user-attachments/assets/f863bbb0-b5c6-4353-bb89-80c3af5e325a" />

### My Query 
<img width="427" alt="image" src="https://github.com/user-attachments/assets/d565a510-e8ef-45f8-b42d-38745b0c9817" />

### Overview of Results Table
<img width="1193" alt="image" src="https://github.com/user-attachments/assets/edc87f35-d7d1-4e6d-90e4-b1e625a9d6bc" />

## Dashboard 
<img width="1025" alt="image" src="https://github.com/user-attachments/assets/09824b78-1ba8-43fe-a9c6-63bb1fe48004" />

