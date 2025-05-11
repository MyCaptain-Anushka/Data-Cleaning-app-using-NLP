# Data-Cleaning-app-using-NLP
Absolutely! Here's the **professional, clean version of your project description** without any emojis or references to Ollama or LLaMA 3.2:

---

# Intelligent Data Cleaning Assistant with Private NLP Interaction

This project is a privacy-focused, intelligent, web-based application built to streamline the data preprocessing workflow for analysts, engineers, and data scientists. Developed using Streamlit, it combines both rule-based logic and locally hosted natural language processing capabilities to detect and resolve common data quality issues—all while keeping your data completely offline.

## Key Features

### Automated Data Inspection

* Automatic classification of column types (Numerical, Categorical, Datetime)
* Detection of missing values, duplicate entries, and statistical outliers

### Interactive Cleaning Operations

* Handle missing values through mean, median, mode, or row removal
* Eliminate duplicate rows with a single click
* Instant visual feedback after each cleaning operation

### Local Natural Language Assistant

* Ask intuitive questions about your dataset in plain English
* Receive smart, context-aware responses powered by a locally running language model
* Examples include: "Which columns have null values?" or "What’s the median score?"

### Visual Analytics

* Generate histograms and boxplots for numerical columns
* Understand data distributions and detect anomalies visually

### Export Functionality

* Download the cleaned dataset as a CSV file after processing

## Project Structure

```
├── Home.py               # Entry point with file upload and navigation
├── DataCleanerApp.py     # Core interface for cleaning, profiling, and visualization
├── ChatWithLlama.py      # Chat interface for NLP interaction (runs locally)
├── cleaning.py           # Data profiling and cleaning logic
├── llama_chat.py         # Handles local natural language processing
```

## Setup Instructions

### 1. Install Required Libraries

Ensure you have Python 3.7 or higher installed, then run:

```
pip install streamlit pandas numpy scipy matplotlib seaborn requests
```

### 2. Launch the Application

Start the web app using:

```
streamlit run Home.py
```

## Usage Guidelines

* Upload your dataset in CSV format via the Home page.
* Navigate between the Data Cleaner and Chat Assistant modules using the sidebar.
* Interactively clean the data and view visualizations in real-time.
* Download the cleaned CSV file once you're finished.

## Technologies Used

| Component       | Technology Used          |
| --------------- | ------------------------ |
| Frontend & UI   | Streamlit                |
| Data Processing | Pandas, NumPy, SciPy     |
| Visualization   | Matplotlib, Seaborn      |
| NLP Interaction | Local Language Model API |

## Contributors

This project was developed as part of an academic exercise to demonstrate the integration of data preprocessing techniques with intelligent, privacy-first NLP interactions.
Developed By
Anushka Patil
Samruddhi Shinde


