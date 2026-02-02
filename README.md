# PSUSphere

### Authors
* **Ralph Justine Beronio**
* **Jan Wilhelm Celedonio**

### Description
PSUSphere is a Django-based web application designed to manage university student organizations. It tracks relationships between colleges, academic programs, students, and their memberships in various campus organizations. This project demonstrates the implementation of Django models, database relationships, and administrative customization.

### Features
* **Data Management**: Robust database models for Colleges, Programs, Organizations, Students, and Memberships.
* **Automated Data Seeding**: Includes a custom management command (`create_initial_data`) using the `Faker` library to populate the database with realistic dummy data.
* **Refactored Admin Panel**:
    * **Colleges**: Searchable by name with date filters.
    * **Programs**: Filterable by college; searchable by program and college name.
    * **Organizations**: Custom list displays with college filters.
    * **Memberships**: Advanced view showing the student's program dynamically within the membership list.
* **Virtual Environment Support**: Configured for easy setup with `requirements.txt`.

### How to Run
1. Activate the virtual environment:
    ```
    source bin/activate  # (Mac/Linux)
    psusenv\Scripts\activate  # (Windows)
2. Install dependencies:
    ```
    pip install -r requirements.txt
    ```
3. Run the server:
    ```
    python manage.py runserver
    ```
