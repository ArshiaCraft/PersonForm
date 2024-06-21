## User Management Project with Django and Vue.js

### Project Description

This project is a simple web application for managing users, built using Django for the backend and Vue.js for the frontend. Users can enter, view, edit, and delete their information, including first name, last name, phone number, and age.

### Features

- **Add User:** Form to add a new user using Vue.js.
- **View Users:** Dynamic display of the user list.
- **Edit Users:** Ability to edit existing user information.
- **Delete Users:** Ability to delete users from the list and the database.

### Technologies

- **Backend:**
  - Django
  - Django REST Framework
  - django-cors-headers
- **Frontend:**
  - Vue.js
  - Axios
  - Bootstrap

### Prerequisites

To run this project, you need to have the following installed:

- Python 3.x
- Node.js
- npm or yarn

### How to Run

#### Backend (Django)

1. Clone the repository:
   ```bash
   git clone https://github.com/username/myproject.git
   cd myproject
   ```

2. Create and activate a virtual environment:
   - Windows:
     ```bash
     python -m venv env
     env\Scripts\activate
     ```
   - macOS/Linux:
     ```bash
     python3 -m venv env
     source env/bin/activate
     ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run database migrations:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. Start the Django development server:
   ```bash
   python manage.py runserver
   ```

#### Frontend (Vue.js)

1. Navigate to the `frontend` directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the Vue development server:
   ```bash
   npm run serve
   ```

### How to Use

1. Open your browser and go to `http://localhost:8080/`.
2. Use the form to add new users.
3. View, edit, and delete users from the list.

### Project Structure

```
myproject/
├── api/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── serializers.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
├── frontend/
│   ├── node_modules/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   ├── PersonForm.vue
│   │   │   ├── PersonList.vue
│   │   ├── App.vue
│   │   ├── main.js
│   ├── package.json
│   ├── README.md
├── myproject/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
├── manage.py
├── requirements.txt
```

### Contribution

If you wish to contribute to this project, you can help by forking the repository and submitting a pull request. You can also help improve the project by reporting bugs and suggesting features in the Issues section.
