AI Engineering & Python Mastery Journey 🚀

Welcome to my learning repository! This project documents my hands-on transition from fundamental Python syntax, file management, and JSON manipulation to building advanced AI applications, integrating with the Google Gemini API, generating vector embeddings, and creating semantic search systems using the local vector database ChromaDB.

📂 Project Structure & Topics Covered

1. Python Basics & Data Handling (Day 1)

Hello.py — First script introducing the execution environment and output.

variables.py — Exploring variables, data types, strings, and formatting (f-strings).

condition.py — Conditional branching using logical operators (if-elif-else).

loops.py — Iterating through collections and processing dictionaries.

students_file.py — Reading and writing text files (.txt) on disk.

json_practice.py — Serialization and deserialization of structured data using the json module.

Project Day 1.py — Capstone mini-project combining conditions, loops, data filtering, and JSON report generation.

2. Object-Oriented Programming (OOP)

Moving forward to encapsulate state and logic using custom Python classes:

ooop.py — Implementation of a Student class featuring data encapsulation, an add_grade method with validation (grades 1–5), and a get_average method to compute grade point averages.

OOP.py — Expanding class concepts by instantiating multiple students (Artem, Nikita, Vlad), printing student details via print_info, and safely updating grades with input validation.

3. LLM Integration & Direct API Calls (Day 2)

Moving away from pre-built interfaces to write raw code interacting with artificial intelligence:

first_api_call.py — Initial request to the Gemini API utilizing environment variables for secure key management (.env + python-dotenv).

chat_with_gemini.py — Interactive console chat (input()) configured with custom system_instruction settings.

chat_with_gemini2.py — Infinite conversation loop (while True) preserving history and context using chat.send_message().

4. Embeddings & Vector Search (Day 3)

Diving under the hood of RAG (Retrieval-Augmented Generation) architectures:

first_embedding.py — Generating multi-dimensional text vector representations via Gemini models and manually computing semantic similarity (cosine similarity) using numpy.

chroma_test.py — Setting up a local vector database using ChromaDB. Integrating a custom embedding function from Gemini (GoogleGenerativeAiEmbeddingFunction), ingesting multi-domain documents (sports, food, technology), and running precise semantic queries (collection.query()).

🛠️ Technology Stack

Python 3.14 — Core programming language.

Google GenAI SDK (google-genai) — Official library for interacting with Gemini models.

ChromaDB — Lightweight local vector database for semantic search.

NumPy — Mathematical operations for cosine similarity calculations.

Python-Dotenv — Secure management of environment secrets and API keys.

⚙️ Quick Start Guide

Clone the repository and install dependencies:

pip install google-genai chromadb numpy python-dotenv


Create a .env file in the root directory and add your API key:

GEMINI_API_KEY="your_actual_gemini_api_key_here"


Run any script (e.g., the ChromaDB test):

python OOP.py python ooop.py
