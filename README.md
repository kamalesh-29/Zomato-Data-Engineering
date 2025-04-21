# Zomato Data Engineering

## Introduction

The goal of this project is to build a data engineering pipeline to analyze Zomato restaurant data. The project involves data extraction, transformation, and loading (ETL) processes, along with visualization and data analysis.

## Technologies Used

- **Programming Language**: Python
- **Web Framework**: Flask
- **Database**: SQL
- **Visualization**: HTML

## Project Structure

- `app_home.html`: Home page of the application.
- `app_index.py`: Main Python application for data extraction and transformation.
- `data_sql.sql`: SQL queries for interacting with the database.
- `home.html`: Home page HTML template.
- `index.html`: Index page HTML template.

## Installation

Follow these steps to set up and run the project on your local machine:

### Prerequisites:
- Python 3.x
- SQL Database (e.g., MySQL, PostgreSQL)
- Flask (for web framework)

### Steps to Install:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/kamalesh-29/Zomato-Data-Engineering.git
   cd Zomato-Data-Engineering
   ```

2. **Set Up Python Environment:**
   - Create a virtual environment (optional but recommended):
     ```bash
     python -m venv venv
     source venv/bin/activate  # For Linux/MacOS
     .\venv\Scripts\activate  # For Windows
     ```

3. **Install Required Libraries:**
   - Install necessary Python libraries:
     ```bash
     pip install -r requirements.txt
     ```

4. **Set Up the Database:**
   - Ensure you have a running SQL database (MySQL/PostgreSQL).
   - Execute the `data_sql.sql` file to create necessary tables and populate them with Zomato restaurant data.
     ```bash
     mysql -u your_user -p your_database < data_sql.sql
     ```
     or for PostgreSQL:
     ```bash
     psql -U your_user -d your_database -f data_sql.sql
     ```

5. **Run the Flask Application:**
   - Start the Flask app:
     ```bash
     python app_index.py
     ```

6. **Access the Application:**
   - Open your browser and go to `http://127.0.0.1:5000/` to view the home page of the application.

## Dataset

The dataset used in this project is the **Zomato Restaurant Data**, which includes various fields such as restaurant name, location, cuisines, user ratings, and more.

## Contribute

Feel free to fork this repository, create a pull request, or open an issue if you have suggestions or improvements.

## License

This project is open-source and available under the [MIT License](LICENSE).


