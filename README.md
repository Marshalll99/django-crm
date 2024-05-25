# CRM

## DESCRIPTION:

 ***This project is a basic Customer Relationship Management (CRM) system built using the Django framework. It utilizes a virtual environment created with venv and leverages uv pip for fast package installation. The front-end is developed using traditional HTML, CSS, and JavaScript. The CRM system allows users to manage customer information, track interactions, and maintain notes, providing a comprehensive tool for customer relationship management.***

## Technologies Used:

- **Backend**: Django Framework
- **Frontend**: HTML, CSS, JavaScript
- **Virtual Environment**: `venv`
- **Package Management**: `pip, uv`

## INSTALLATION:
### 1. Create a Virtual Environment:
  ```bash
  python -m venv .venv
  ```
- use uv pip:
  ```bash
    uv venv
  ```
### 2. Activate the Virtual Environment: 
* On Windows:
  ```bash
  source .venv\Scripts\activate
  ```
* On macOS and Linux:
  ```bash
  source .venv/bin/activate
  ```
### 3. Install Django:
  ```bash
  uv pip install Django
  ```
### 4. Create a new Django app:
  ```bash
  django-admin startproject <project_name>
  ```
### 5. Run the Development Server:
  ```bash
  python manage.py runserver
  ```
### 6. Access the Application:
  Open your web browser and go to 'http://127.0.0.1:8000/'.    
## License:
  This project is licensed under the MIT License. See the LICENSE file for more details.
## Contact:
  For any questions or feedback, please reach out to [mymailadrees@email.com].  