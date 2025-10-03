# 🎨 GEN_Project_For_Retail_Store: Talk to a Database  

**GEN_Project_For_Retail_Store** is an *end-to-end LLM project* that allows users to **interact with a MySQL database using natural language**. The system converts user questions into **SQL queries**, executes them on the database, and returns **accurate answers**.  

This project simulates a **T-shirt retail store** where inventory, sales, and discounts are tracked in MySQL. A store manager can ask questions like:  

- *How many white Adidas T-shirts are left in stock?*  
- *How much sales revenue will be generated if all extra-small T-shirts are sold today?*  

The system intelligently **generates SQL queries** and executes them automatically.

---
## 💡 Project Overview

This project demonstrates:

- **Integration of LLMs with databases**  
- Building **interactive web apps** using Streamlit  
- Using **embeddings** and **few-shot learning** for natural language understanding  

The store in this project sells T-shirts from brands: **Adidas, Nike, Levi’s, Van Heusen**. The system handles:  

- Inventory management 🛒  
- Sales tracking 💰  
- Discount calculations 💸  

---
## ✨ Key Features

- **Natural Language to SQL:** Ask questions in plain English, get SQL queries automatically generated  
- **Intelligent Query Execution:** Executes queries on MySQL and returns results  
- **Interactive UI:** Built using Streamlit for easy user interaction  
- **Vector Store & Embeddings:** Uses ChromaDB and Hugging Face embeddings for semantic understanding  
- **Few-shot Learning:** Improves the accuracy of generated SQL queries  
- **Supports Multiple Brands:** Adidas, Nike, Levi's, Van Heusen  

---
## 🛠 Installation Guide

Follow these steps to run the project locally:

```bash
# Clone the repository
git clone https://github.com/RohitGautam7972/GEN_Project_For_Retail_Store.git

# Navigate to the project folder
cd GEN_Project_For_Retail_Store

# Install required dependencies
pip install -r requirements.txt
