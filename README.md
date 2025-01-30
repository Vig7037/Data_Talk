# Intelligent SQL Query Chat App

## Overview
This app uses Google's Gemini AI model to convert natural language questions into SQL queries and execute them on an SQLite database via a Streamlit interface.

## Features
- AI-powered SQL query generation
- SQLite database integration
- Streamlit-based UI

## Installation
```sh
git clone https://github.com/your-repo/intelligent-sql-chat-app.git
cd intelligent-sql-chat-app
pip install -r requirements.txt
```

## Usage
1. Create a `.env` file and add:
   ```sh
   GOOGLE_API_KEY=your_google_api_key_here
   ```
2. Run the app:
   ```sh
   streamlit run app.py
   ```

## Example Queries
- "How many records are present?" → `SELECT COUNT(*) FROM STUDENT;`
- "List students in Data Science class." → `SELECT * FROM STUDENT WHERE CLASS='Data Science';`

## License
MIT License

