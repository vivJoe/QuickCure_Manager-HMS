|-- QuickCure_Manager-HMS
    |-- __init__.py (Initialize the Flask application.)
    |-- routes.py (Define URL routes and corresponding view functions.)
    |-- models.py (Define database models using SQLAlchemy for SQLite3.)
    |-- templates
        |-- index.html (landing page)
        |-- auth
            |-- patient_registration.html (Page for patient registration.)
            |-- login.html (Login page.)
        |-- appointment_scheduling.html (Page for appointment scheduling.)
        |-- staff_management.html (Admin Page)
        |-- patient.html (Patient's Profile)
        |-- base.html (Base template containing common elements)
        |-- doctors.html (Doctor's Page)
    |-- static
        |-- css
            |-- styles.css (Custom styles for the application.)
        |-- js
            |-- main.js (Custom JavaScript functions for client-side logic.)
    |-- config.py
    |-- run.py
|-- venv
|- .gitignore