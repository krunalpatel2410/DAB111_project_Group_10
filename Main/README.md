**Obesity Insights Web Application**

This project aims to provide insights into obesity using data collected from Kaggle. 
The web application retrieves obesity-related data from a SQLite database and presents it in a user-friendly format, allowing users to gain valuable insights into the factors contributing to obesity.

**Overview**

The Obesity Insights Web Application serves as a valuable resource for understanding the complexities of obesity. By analyzing data collected from Kaggle, the application aims to shed light on various factors influencing obesity rates and provide actionable insights for researchers, healthcare professionals, and policymakers.

**Features**

* Data-driven insights into obesity based on the Kaggle dataset.
* User-friendly web interface for easy navigation and exploration of obesity-related data.
* The About page provides information about the data source and variable definitions.
* Data page displaying the obesity dataset or a sample thereof.

**Requirements**

To run the Obesity Insights Web Application locally, ensure you have the following installed:

* Python 3.x
* Flask
* pandas
* sqlite3

**Installation**

To install and run this project locally, follow these steps:

Prerequisites
* Python (version X.X)
* pip (package manager)

1. Clone the repository
**https://github.com/krunalpatel2410/DAB111_project_Group_10.git**

2. Install the required dependencies using the command:
**pip install -r requirements.txt**

3. Configure the database path
In the website.py file, locate the database configuration section. By default, it may look like this:
**'C:\Users\sonup\Documents\GitHub\DAB111_project_Group_10\Main\database'**

* Change 'path/to/your/database.db' to the desired path where you want to store your database file. For example: **DATABASE_PATH = 'data/obesity_data.db'**

4. Run the application
**website.py**
The website should now be running locally. You can access it at http://localhost:5000 in your web browser.

**Usage**

Once the application is running, you can:
Explore insights into obesity by navigating to the Data page.
Learn more about the data source and variable definitions on the About page.

**Data Source**

The obesity-related data used in this project is collected from Kaggle, a platform for datasets and data science projects.
The dataset includes information on various factors influencing obesity, such as demographics, lifestyle habits, and health indicators.

**Acknowledgments**

Special thanks to Kaggle for providing the obesity dataset used in this project.
