# Django Blog Site
Welcome to the Django Blog Site! This is a simple blog application built with Django, allowing users to create, edit, and publish blog posts.

## Getting Started

### Prerequisites

- Python 3.x
- Django 3.x

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/roranwillias/blog.git
   ```

2. Navigate to the project directory:

   ```bash
   cd blog
   ```

3. Create a virtual environment:

   ```bash
   # On Windows
   python -m venv venv

   # On macOS/Linux
   python3 -m venv venv
   ```

4. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS/Linux:

     ```bash
     source venv/bin/activate
     ```

5. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

6. Apply migrations:

   ```bash
   python manage.py migrate
   ```

7. Create a superuser account:

   ```bash
   python manage.py createsuperuser
   ```

   Follow the prompts to set up your admin account.

8. Run the development server:

   ```bash
   python manage.py runserver
   ```

   The blog site will be accessible at [http://127.0.0.1:8000/](http://127.0.0.1:8000/).

## Usage

- Access the admin panel at [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/) to manage blog posts.

- Visit [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to view and interact with the blog.

## Basic Commands

- **Activate Virtual Environment:**
   ```bash
   # On Windows
   venv\Scripts\activate

   # On macOS/Linux
   source venv/bin/activate
   ```

- **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

- **Apply Migrations:**
   ```bash
   python manage.py migrate
   ```

- **Create Superuser:**
   ```bash
   python manage.py createsuperuser
   ```

- **Run Development Server:**
   ```bash
   python manage.py runserver
   ```

- **Create a New Django App:**
   ```bash
   python manage.py startapp <app_name>
   ```

   Replace `<app_name>` with the desired name for your new app.

- **Generate Migrations for Changes:**
   ```bash
   python manage.py makemigrations
   ```

- **Apply Migrations After Changes:**
   ```bash
   python manage.py migrate
   ```

## Contributing

Feel free to contribute to the development of this project. Follow the [CONTRIBUTING.md](CONTRIBUTING.md) guidelines for more information.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

Feel free to customize the sections and commands based on the specifics of your project. This README provides a comprehensive guide for setting up, running, and contributing to your Django Blog Site.
