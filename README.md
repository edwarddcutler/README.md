# README.md
# Superstore Sales Dashboard

A web application built using Flask and Pandas to analyze and filter Superstore sales data. Users can filter data by year, category, and region and view the results in a user-friendly dashboard.

## **Project Structure**
my_flask_app/ ├── app.py # Main Flask application ├── templates/ │ └── index.html # HTML template for the dashboard ├── static/ │ └── style.css # Optional CSS for styling └── data/ └── superstore_sales.csv # Superstore sales dataset (CSV file)

## **Setup Instructions**

1. **Clone the repository:**
   git clone <repository-url>
   cd my_flask_app

2. **Install required libraries: Make sure you have Python 3.7+ installed. Install Flask and Pandas using:**
pip install flask pandas

3. **Add the dataset: Place the superstore_sales.csv file in the data/ folder. Ensure the dataset has columns like:**
Order Date (Dates of orders)
Category (Product categories)
Region (Regions of sales)
Sales (Sales amounts)

**Run the Application**
Start the Flask server:

python app.py
Open the application in a web browser: Go to http://127.0.0.1:5000.

Interact with the dashboard:

Use the dropdown menus to filter sales data by year, category, or region.
View the filtered results and total sales displayed on the page.

**Customization**
Add Queries: Modify app.py to include additional filtering or custom queries.
Improve Styling: Edit static/style.css for better UI/UX.

**Dependencies**
Python 3.7+
Flask
Pandas
To install dependencies, run:

pip install flask pandas

**Happy Analyzing!**
This `README.md` file provides a clear overview, setup instructions, and guidance for running the application. Let me know if you need to adjust it further!
