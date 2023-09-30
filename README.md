# Django-React Integration Project

This project demonstrates the integration of Django as a backend and React as a frontend to create a simple web application. The application allows users to input their name and email, which is then displayed both in the Django Rest Framework and on the React frontend.

<img width="945" alt="image" src="https://github.com/SuryaPratap2542/Django-React/assets/89827931/1cbadb2d-594b-433c-9f82-f66f34ec2e3f">

**Description:** This screenshot shows the Django backend where user data input .

<img width="941" alt="image" src="https://github.com/SuryaPratap2542/Django-React/assets/89827931/da27f363-6da8-4e56-a787-8013611609c0">

**Description:** This screenshot shows the Django API app named `api` located inside the `djangobackend` folder.


<img width="909" alt="image" src="https://github.com/SuryaPratap2542/Django-React/assets/89827931/25a39573-377c-4173-aff1-7cc93ee55484">

**Description:** This screenshot displays the React frontend where user data is displayed.



## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed on your system.
- Python and Django installed on your system.

## Installation and Setup

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/django-react-integration.git
   ```

2. Change into the project directory:

   ```bash
   cd django-react-integration
   ```

3. Set up the Django backend:

   - Create a virtual environment:

     ```bash
     python -m venv venv
     ```

   - Activate the virtual environment:

     - On Windows:

       ```bash
       venv\Scripts\activate
       ```

     - On macOS and Linux:

       ```bash
       source venv/bin/activate
       ```

   - Install Django and other dependencies:

     ```bash
     pip install -r requirements.txt
     ```

   - Apply migrations and run the Django server:

     ```bash
     python manage.py migrate
     python manage.py runserver
     ```

   The Django API should now be accessible at http://localhost:8000/api/student/.

4. Set up the React frontend:

   - Change into the `frontend` directory:

     ```bash
     cd frontend
     ```

   - Install frontend dependencies:

     ```bash
     npm install
     ```

   - Start the React development server:

     ```bash
     npm start
     ```

   The React frontend should now be accessible at http://localhost:3000/.

## Usage

1. Access the React frontend at http://localhost:3000/.

2. Enter your name and email in the form on the homepage and click "Submit."

3. The data you entered will be displayed on the same page.

4. To view the data in the Django Rest Framework, visit http://localhost:8000/api/student/ in your browser or use an API client like [Postman](https://www.postman.com/).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
