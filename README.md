Generics-Views-DRF

A basic Django REST API for managing books, built with Django REST Framework (DRF) and Generics Views method.
API Endpoints

    GET /api/books/ - Lists all books
    POST /api/books/ - Creates a new book
    GET /api/books/<int:pk>/ - Retrieves details of a specific book
    PUT /api/books/<int:pk>/ - Updates a specific book
    DELETE /api/books/<int:pk>/ - Deletes a specific book

Setup

1.Clone the repository:

    git clone <repository-url>

2.Install dependencies:

    pip install -r requirements.txt

3.Run migrations:

    python manage.py migrate

4.Start the development server:

    python manage.py runserver

Usage

After starting the server, you can access the API at http://127.0.0.1:8000/api/books/.

![Screenshot from 2024-11-02 11-47-15](https://github.com/user-attachments/assets/f83e2c7f-8401-48ca-b720-ece4bfe77229)
![Screenshot from 2024-11-02 11-47-33](https://github.com/user-attachments/assets/b743db39-4c49-4874-bc21-47fc2241685a)

