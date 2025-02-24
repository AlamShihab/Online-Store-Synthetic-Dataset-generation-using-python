# Online-Store-Synthetic-Dataset-generation-using-python
This project generates synthetic sales data with realistic patterns, including high sales for electronics, beauty, automotive, and select books.

E-Commerce Sales Data Generator

Overview

This project generates synthetic e-commerce sales data, including products, customers, and orders. The dataset incorporates realistic sales trends, seasonal variations, and customer purchasing behaviors. It can be used for data analysis, machine learning experiments, and business intelligence applications.

Features

Product Data Generation: Generates a dataset of products across multiple categories with logical price ranges.

Customer Data Generation: Simulates customer profiles with demographic attributes.

Order Data Generation: Creates orders with realistic purchasing patterns, including seasonal spikes and high-demand products.

Behavioral Patterns:

High sales for electronics, beauty, and automotive products.

High demand for books like "Self-Help Book", "Comic Book", and "Novel".

Peak sales at the end of November and throughout December.

Majority of consumers place multiple orders with recognizable patterns.

Data Quality Variations:

Inclusion of outliers for testing robustness.

Missing values for simulating real-world data challenges.

Installation

Clone the repository:

git clone https://github.com/your-repo/ecommerce-data-generator.git

Install dependencies:

pip install pandas numpy

Run the script:

python generate_data.py

Usage

Modify the script to adjust the number of records.

Use the generated CSV files for data analysis or machine learning projects.

Integrate with other data processing pipelines.

File Structure

├── generate_products.py   # Script to generate product data
├── generate_customers.py  # Script to generate customer data
├── generate_orders.py     # Script to generate order data
├── data/                  # Folder containing generated datasets
│   ├── products.csv
│   ├── customers.csv
│   ├── orders.csv
├── README.md              # Project documentation

Contribution

Fork the repository and submit pull requests.

Report any issues or feature requests via GitHub Issues.

License

This project is licensed under the MIT License.

Contact

For questions or suggestions, feel free to reach out!
