# Nutrition Calculator

## Project Overview
This Nutrition Calculator is a Django web application that allows users to track their daily nutritional intake, log meals, and monitor their dietary goals.

## Learning Objectives
- Master Django framework fundamentals (models, views, templates)
- Implement user authentication and authorization
- Build database relationships and migrations
- Create forms and handle user input validation
- Deploy a Django application

## Setup Instructions

### Prerequisites
- Python 3.8+
- pip
- Git

### Installation
1. Clone the repository:
```bash
git clone https://github.com/Zivica/nutrition-calc.git
cd nutrition-calc
```

2. Create virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run migrations:
```bash
python manage.py migrate
```

5. Create superuser:
```bash
python manage.py createsuperuser
```

6. Start development server:
```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` to see your application.

## License
MIT License
