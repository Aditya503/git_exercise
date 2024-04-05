
# Assignment 5 - SQL Database Connection and Querying with Python

## Welcome!

This project demonstrates how to use Python, specifically the pandas library, to connect to a SQL database, execute SQL queries, and read the results into pandas DataFrames. It covers the basics of setting up a database connection using SQLAlchemy and pymysql, executing simple and complex SQL queries, and preprocessing data for further analysis. By the end of this project, users will be well-equipped to leverage Python for data extraction and preprocessing from SQL databases.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

## Pre-requisites

To run this project, you'll need the following installed:
```bash
Python 3
pandas library
SQLAlchemy
pymysql
```




## Installation

Follow these steps to get a development environment running:

Install the required Python packages if you haven't already. You can install them using pip:

```bash
  pip install pandas sqlalchemy pymysql
```
Clone the repository to your local machine (or download the project files).

Navigate to the project directory where the notebook Lab1.ipynb is located.
## Running Tests

This project does not include automated tests. The focus is on demonstrating the process of connecting to a SQL database and querying data with Python but one process of testing can be included to test the connection to the SQL database.


## Deployment

To deploy this on a live system, ensure you have a live SQL database accessible and modify the database connection string within the notebook to match your live database credentials:

```
engine = create_engine('mysql+pymysql://user:password@host:port/database')

```


## Built with

```
pandas - Used for data manipulation and analysis
SQLAlchemy - Database toolkit for Python
pymysql - MySQL database connector for Python
```
## Authors

- [@Aditya503](https://github.com/Aditya503)

## License

[MIT](https://choosealicense.com/licenses/mit/)


## Acknowledgements

 - Professor: Omar Al Trad, for giving us the lecture notes and corresponding lab files for practice.
