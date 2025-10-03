GEN_Project_For_Retail_Store: Talk to a Database

This is an end-to-end LLM project built using Google PaLM API and LangChain.
It allows users to interact with a MySQL database using natural language.
The system converts user questions into SQL queries, executes them, and returns accurate results.

The project simulates a T-shirt retail store that maintains inventory, sales, and discounts data.
A store manager can ask questions such as:

How many white Adidas T-shirts are left in stock?

What is the total sales if all extra-small T-shirts are sold with discounts applied?

The system intelligently generates SQL queries and executes them on the MySQL database.

Project Highlights

Retail store inventory for brands like Adidas, Nike, Levi's, and Van Heusen.

Inventory, sales, and discount data stored in MySQL.

LLM-based Q&A system using:

Google PaLM LLM

Hugging Face embeddings

Streamlit for UI

LangChain framework

ChromaDB as a vector store

Few-shot learning

The store manager can ask questions naturally, and the system will produce SQL-based answers instantly.

Installation

Clone this repository:

git clone https://github.com/RohitGautam7972/GEN_Project_For_Retail_Store.git


Navigate to the project folder:

cd GEN_Project_For_Retail_Store


Install dependencies:

pip install -r requirements.txt


Add your Google PaLM API key in .env:

GOOGLE_API_KEY="your_api_key_here"


Set up the MySQL database:
Run database/db_creation_atliq_t_shirts.sql in MySQL Workbench.

Usage

Run the Streamlit app:

streamlit run main.py


The web app will open in your browser. Ask questions in natural language to get answers from the database.

Sample Questions

How many total T-shirts are left in stock?

How many Nike T-shirts are available in XS size and white color?

What is the total price of all S-size T-shirts in inventory?

How much sales revenue will be generated if all small Adidas T-shirts are sold today after discounts?

Project Structure

main.py: Streamlit application

langchain_helper.py: LangChain logic

requirements.txt: Python dependencies

few_shots.py: Few-shot learning prompts

.env: Google API key configuration
