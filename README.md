🧪 Product Store API Testing Project

This is a **mini API automation project** built using **Postman**, **Newman**, and the `htmlextra` reporter plugin.  
It covers **GET and POST request testing**, **schema validation**, **mock server setup**, and **data-driven testing** — all packed into a professional HTML report.

📦 Project Structure : 
Product-Store-API-Test/
├── collection/
│ └── ProductStore.postman_collection.json ← Final Postman collection
│
├── data/
│ └── orders.csv ← Used for data-driven POST testing
│
├── reports/
│ └── final-report.html ← Beautiful Newman HTML report

🎯 Project Objective

The goal of this project is to test the **Product Store APIs**, covering:

- ✅ GET `/products` — List all products
- ✅ POST `/order` — Place an order (via CSV data)
- ✅ Schema validation for API responses
- ✅ Status and key verification in responses
- ✅ Data-driven testing (looping orders from a CSV file)
- ✅ HTML Report generation using Newman

🧪 Tools & Technologies Used

| Tool        | Purpose                          |
|-------------|----------------------------------|
| Postman     | API request creation & testing   |
| Newman      | Command-line test runner         |
| htmlextra   | Plugin to generate HTML reports  |
| CSV (orders.csv) | Data-driven test input     |


