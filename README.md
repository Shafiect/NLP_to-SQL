# NLP_to_SQL
Use NLP to query SQL and avail tabular data - using gpt-3 completion API
This project is designed to allow users to query data from a CSV file using natural language text and converting the text into SQL queries.

Getting Started :

Prerequisites :
  Python 3.x,
  pandas library,
  sqlalchemy library,
  openai library
  
Installing Dependencies:
  pip install pandas
  pip install sqlalchemy
  pip install openai
  
Data Source :
  The sample data used in this project is stored in a CSV file named "sales_data_sample.csv".

Running the Program :
  Clone this repository to your local machine.
  Open nlp_to_sql.py in your Python editor of choice.
  Run the fnctn() function to execute the program.
  Follow the prompts to enter natural language text and retrieve data from the CSV file.
  
How it Works : 
  The program reads the data from the CSV file using the pandas library.
  The data is then converted into a SQL table using the sqlalchemy library and stored in an in-memory SQLite database.
  The user is prompted to enter natural language text describing the data they want to retrieve.
  The natural language text is passed to OpenAI's GPT-3 API, which generates a SQL query based on the text.
  The generated SQL query is executed against the in-memory SQLite database using the sqlalchemy library.
  The program returns the results of the SQL query to the user.
  
Contributing :
  We welcome contributions to this project. Please follow the following steps:
  Fork this repository.
  Create a new branch.
  Make your changes and commit them with descriptive commit messages.
  Push your changes to your forked repository.
  Submit a pull request.
