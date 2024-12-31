Django Poll App

Description:
This project is a simple Django-based Poll App website. Users can create, view, and vote on polls. It demonstrates my ability to build a full-stack web application using Django, a powerful Python-based web framework. This project is significant as it highlights my skills in backend development, database integration, and web app deployment.

Table of Contents:
1. Description
2. Installation
3. Usage
4. Features
5. Credits

Installation:
To set up and run this project locally, follow these steps:

1. Clone the repository:
   git clone ...
   2 – Introduction to Software Engineering/L2T20 – Django – Poll App/mySite/polls

3. Navigate to the project directory:
   cd django-poll-app

4. Create a virtual environment and activate it:
   python -m venv venv
   source venv/bin/activate   # For Linux/Mac
   venv\Scripts\activate      # For Windows

5. Install the required dependencies:
   pip install -r requirements.txt

6. Apply migrations to set up the database:
   python manage.py migrate

7. Start the development server:
   python manage.py runserver

Usage:
1. Open your web browser and navigate to http://127.0.0.1:8000/.
2. View the list of polls, create a new poll, or vote on existing polls.
3. Use the admin panel at http://127.0.0.1:8000/admin/ for managing polls (requires admin login credentials).

Screenshots:
Homepage Example:
![image](https://github.com/user-attachments/assets/9d2231e2-0ffe-4d32-af56-8567da0b0cc3)


Poll Voting Page Example:
![image](https://github.com/user-attachments/assets/1dc33996-936f-4d49-9b28-9a21dc718881)


Features:
- Create, view, and manage polls.
- Users can vote on polls with real-time results displayed.
- Admin panel for managing polls and users.
- Built using Django's MVC architecture.

Credits:
This project was created by Muhammed Uzair as part of the HyperionDev Software Engineering Bootcamp. Special thanks to my mentors for their guidance and feedback.
