# dhanvin

dhanvin

## About the Project

This project is a profile management system designed to showcase and manage user profiles efficiently. It includes features for creating, updating, and viewing profiles with a user-friendly interface.

## Project Setup and Configuration

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/Huggiv/dhanvin.git
   cd dhanvin
   ```

2. **Create a Virtual Environment**  
   Ensure you have Python installed, then create and activate a virtual environment:  
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**  
   Install the required Python packages:  
   ```bash
   pip install -r requirements.txt
   ```

4. **Environment Configuration**  
   Create a `.env` file in the project root and configure the required environment variables. Example:  
   ```env
   FLASK_APP=app.py
   FLASK_ENV=development
   DATABASE_URL=your-database-url
   ```

5. **Run the Application**  
   Start the Flask development server:  
   ```bash
   flask run
   ```

6. **Run Tests**  
   To run the test suite, use:  
   ```bash
   pytest
   ```

7. **Deploy the Application**  
   Use a production-ready WSGI server like Gunicorn:  
   ```bash
   gunicorn -w 4 app:app
   ```
