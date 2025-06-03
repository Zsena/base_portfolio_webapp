# Personal Portfolio WebApp

This is a simple portfolio web application built with Django, Bootstrap, Python, and SQLite. The goal is to showcase your professional profile and projects.

## 📁 Project Structure

```
├── pages/                  # Static pages (e.g., About, Contact)
├── personal_portfolio/     # Main Django configuration project
├── projects/               # Portfolio projects app
├── templates/              # HTML templates (Bootstrap based)
├── uploads/project_images/ # Uploaded project images
├── venv/                   # Python virtual environment (excluded from version control)
├── db.sqlite3              # SQLite database
├── manage.py               # Django management script 
```

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/portfolio-webapp.git
   cd portfolio-webapp
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate 
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run database migrations:
   ```bash
   python manage.py migrate
   ```

5. Start the development server:
   ```bash
   python manage.py runserver
   ```

6. Open your browser and visit:
   [http://127.0.0.1:8000](http://127.0.0.1:8000)

## ✅ Features

- About Me page
- Contact form
- Projects listing and detail pages
- Upload images for each project
- Responsive Bootstrap-based layout

## 🧰 Built With

- Python 3.x
- Django 3.x
- Bootstrap 4 or 5
- SQLite

## 📌 Notes

- The `venv/` folder and `__pycache__/` files should be added to `.gitignore`
- For production, remember to update `DEBUG = False` and configure a secure database

## 📬 Contact

Developer: **Zsena**  
Email: [zsanett.tamas87@gmail.com](mailto:zsanett.tamas87@gmail.com)