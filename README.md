# Django Authentication Project

This is a Django web application for user authentication, built with Django Rest Framework (DRF) and Simple JWT in the backend, and React.js in the frontend.

## Features

- User Registration: Users can register and create an account.
- User Login: Registered users can log in to their accounts.
- Token-based Authentication: JWT (JSON Web Tokens) are used for authentication.
- Access and Refresh Tokens: Implementing access and refresh tokens for secure authentication and token refresh.
- User Profile: Users can view and update their profile information.
- Frontend with React.js: The frontend is built with React.js for a dynamic user interface.

## Technologies Used

- Backend:
  - Django: Python-based web framework for building robust web applications.
  - Django Rest Framework (DRF): Toolkit for building RESTful APIs.
  - Simple JWT: Library for implementing JWT-based authentication in Django.

- Frontend:
  - React.js: JavaScript library for building interactive user interfaces.
  - React Router: Library for handling client-side routing in a React application.
  - Axios: HTTP client library for making API requests.

## Installation and Setup

1. Clone the repository:
```bash
git clone https://github.com/as4c/Authentication-App.git
```


2. Change into the project directory:

cd django-authentication-project

markdown


3. Set up the backend:
- Create and activate a virtual environment.
- Install the required Python dependencies from the `requirements.txt` file:
  ```
  pip install -r requirements.txt
  ```
- Set up the database and apply migrations:
  ```
  python manage.py migrate
  ```
- Start the Django development server:
  ```
  python manage.py runserver
  ```

4. Set up the frontend:
- Change into the `frontend` directory:
  ```
  cd frontend
  ```
- Install the required Node.js dependencies:
  ```
  npm install
  ```
- Start the React development server:
  ```
  npm start
  ```

5. Open your web browser and visit `http://localhost:3000` to access the application.

## Configuration

Before running the app, make sure to configure the following settings:

- Backend:
- Update the database settings in the `settings.py` file.
- Configure Simple JWT settings for token authentication.

- Frontend:
- If necessary, update the API endpoint URLs in the frontend code to match your backend setup.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature/fix:

git checkout -b feature/my-feature

markdown

3. Make your changes and commit them:

git commit -m "Add new feature"

css

4. Push the changes to your forked repository:

git push origin feature/my-feature

csharp

5. Open a pull request on the original repository.

## License

This project is licensed under the [MIT License](LICENSE).