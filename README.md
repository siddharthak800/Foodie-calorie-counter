# FOODIE-CALORIE-COUNTER - Meal Nutrition Calculator 🥗

A web application that calculates comprehensive nutrition information for meals using natural language input. Built with Django and powered by a Python-based nutrition API.

## Features ✨

- **Real-time Nutrition Analysis**
  - Instant calculation of calories
  - Detailed macro-nutrients breakdown
  - Vitamin and mineral content
  - Portion size adjustments

- **User-Friendly Interface**
  - Natural language meal input
  - Interactive nutrition charts
  - Mobile-responsive design
  - Save favorite meals

- **Detailed Reports**
  - Daily nutrition summaries
  - Weekly nutrition trends
  - Exportable data in CSV format

## Tech Stack 🛠️

- **Frontend**
  - HTML5
  - CSS3
  - JavaScript (ES6+)


- **Backend**
  - Python 3.8+
  - Django 4.0+
  - Django REST Framework
  - SQLite (default database)

- **API Integration**
  - Custom Python nutrition calculation API
  - RESTful architecture
  - JSON response format

## Installation 🚀

1. Clone the repository:
   
https://github.com/siddharthak800/Foodie-calorie-counter.git
   

2. Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r "name of library" (on imports of the .py file)
   ```

4. Set up environment variables:
   Create a `.env` file in the root directory:
   ```env
   DEBUG=True
   SECRET_KEY=your_secret_key
   NUTRITION_API_KEY=your_api_key (provided in the code)
   ```



5. Access the application at `http://localhost:8000`



## Screenshots 📸

### Home Page
![homepagefoodie](https://github.com/user-attachments/assets/4679c27e-bade-4b2c-bde8-fcc71572b70b)

### Results Dashboard
![results](https://github.com/user-attachments/assets/8b4bc090-6a9b-4b44-b251-75adc86327c9)



## Configuration ⚙️

### Environment Variables
```env
DEBUG=True/False
SECRET_KEY=django_secret_key
NUTRITION_API_KEY=your_api_key
DATABASE_URL=your_database_url
```

### Database Configuration
```python
# config/settings.py

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.sqlite3',
        'NAME': BASE_DIR / 'db.sqlite3',
    }
}
```

