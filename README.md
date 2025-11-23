# eHospital Project

This is the eHospital project, an Electronic Health Monitoring System that provides a comprehensive healthcare management platform for patients, doctors, and administrators.

## About Me

I am Shubham Kumar, the developer of this project. I am passionate about building healthcare software solutions to improve patient care and streamline medical workflows.

## Project Overview

- Developed using Django 5.2.8
- Features user roles like patient, doctor, and administrator
- Patients can access health records, book doctor appointments, and communicate with healthcare providers
- Doctors can manage patient records, view test results, and provide consultations
- Administrators manage system settings and user accounts
- Uses django-crispy-forms for UI components and django-cors-headers for cross-origin requests
- Supports login/logout, password reset, and profile management
- Includes integration endpoints for NodeMCU devices

## Running the Project

1. Create and activate a virtual environment
2. Install dependencies from `requirements.txt`:
   ```
   pip install -r requirements.txt
   ```
3. Set up environment variables as needed (email settings, NodeMCU server, etc.)
4. Run database migrations:
   ```
   python manage.py migrate
   ```
5. Create a superuser for admin access:
   ```
   python manage.py createsuperuser
   ```
6. Start the development server:
   ```
   python manage.py runserver
   ```
7. Access the project at [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Contact

For questions or support, please contact Shubham Kumar.
