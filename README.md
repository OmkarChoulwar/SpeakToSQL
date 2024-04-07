# SpeakToSQL
<h3>Overview</h3>
This project aims to facilitate the conversion of natural human language queries into SQL queries, allowing users to interact with databases more intuitively. With this tool, users can input plain English queries and receive SQL queries as output, along with the result of executing these SQL queries in a plain text format.

<h3>Features</h3>

- Natural Language Understanding: The system is capable of understanding natural language queries, parsing them to identify key entities and operations.
- SQL Query Generation: Once the natural language query is understood, the system generates SQL queries that capture the user's intent.
- Database Interaction: The generated SQL queries are executed against a specified database, and the results are returned in a plain text format for easy understanding.

<h3>Usage</h3>

- Input: Users provide a natural language query as input to the system i.e gradio interface
- SQL Generation: Based on the parsed query, the LLM Model generates corresponding SQL queries.
  Below can be seen based on the user query, the LLM Model creates a SQL Query by selecting relevant tables and crafting appropriate queries
  ![LLM_Query_Creation](https://github.com/OmkarChoulwar/SpeakToSQL/assets/55315055/e4a7c8e9-83b8-44e7-a5c7-eba5fb14969c)

- Database Interaction: The generated SQL queries are executed against the specified database.
- Output: The results of the SQL queries are returned in plain text format, providing users with the requested information on the gradio interface


A sample snapshot of the output generated can be seen here:
![Text-to-SQL](https://github.com/OmkarChoulwar/SpeakToSQL/assets/55315055/65682c55-b10a-44b2-be0d-2ba7ec40378b)
