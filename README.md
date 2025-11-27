# Adventure Works Data Engineering Project

## 📊 Project Overview
This project is an end-to-end Data Engineering solution designed to ingest, process, and transform the **Adventure Works** dataset. The goal is to build a robust data pipeline that organizes data into a structured format suitable for analytics and reporting.

The project follows the **Medallion Architecture** (Bronze, Silver, Gold layers) to ensure data quality and modularity.

## 📂 Repository Structure

```text
├── Data/                   # Contains raw source data files (CSV/JSON)
├── silver_layer.ipynb      # Jupyter Notebook for transforming raw data to the Silver Layer
└── README.md               # Project documentation
🏗️ Architecture
The pipeline is designed to move data through the following stages:

Bronze Layer (Raw): Ingestion of raw data from the Data/ folder.

Silver Layer (Transformed): Cleaning, filtering, and joining tables to create enriched datasets. (Handled by silver_layer.ipynb).

Gold Layer (Curated): [Future Scope] Aggregation of data for business intelligence and reporting.

🛠️ Technologies Used
Language: Python

Data Processing: Pandas / PySpark (via Jupyter Notebook)

Data Storage: Local File System / Data Lake

Source Data: Adventure Works (Sales, Products, Customers, etc.)

🚀 Getting Started
Prerequisites
Python 3.x installed

Jupyter Notebook or JupyterLab

Required Python libraries:

Bash

pip install pandas numpy pyspark
How to Run
Clone the repository:

Bash

git clone [https://github.com/vinayakdataexpert/Adventure-Works-Data-Engineering-Project.git](https://github.com/vinayakdataexpert/Adventure-Works-Data-Engineering-Project.git)
Navigate to the project directory:

Bash

cd Adventure-Works-Data-Engineering-Project
Launch Jupyter Notebook:

Bash

jupyter notebook
Execute the Pipeline:

Open silver_layer.ipynb.

Run all cells to process the data from the Data/ folder and generate the Silver Layer outputs.

📈 Dataset
The project uses the Adventure Works sample database, which includes realistic scenarios for:

Sales: Transactional data.

Products: Product details, categories, and subcategories.

Customers: Customer demographics and information.

🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
