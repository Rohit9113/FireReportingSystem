# Fire Reporting System
The Fire Reporting System is a web application developed using the Django framework. It provides a platform for users to report fire incidents and enables the management of these incidents by authorized personnel. This README file provides an overview of the project and instructions for running and configuring the system.

## Features
The Fire Reporting System includes the following features:

1. Incident Reporting: Authenticated users can report fire incidents by providing relevant information such as location, type of fire, and additional details.
2. Incident Management: Authorized personnel can view and manage reported incidents, including assigning them to specific responders and updating their status.
3. Dashboard: The system provides a dashboard that displays statistical information about reported incidents, such as the number of incidents per location or type.
4. Search and Filtering: Users can search and filter incidents based on various criteria, such as location, status, or date.

## Technologies Used
The Fire Reporting System is built using the following technologies:

1.Django: A high-level Python web framework that provides a clean and efficient way to develop web applications.
2. HTML: The standard markup language for creating web pages.
3. CSS: A stylesheet language used to describe the presentation of a document written in HTML.
4. Bootstrap: A popular CSS framework that provides pre-designed components and styles to facilitate responsive web design.
5. JavaScript: A programming language used for client-side scripting to enhance user interactivity.
6. SQLite: A lightweight relational database management system used as the default database backend for Django.

## Installation and Setup

To run the Fire Reporting System on your local machine, follow these steps:

1. Clone the repository to your local machine:
**git clone https://github.com/your-username/fire-reporting-system.git**

2. Change to the project's directory:
**cd fire-reporting-system**

3. (Optional) Create and activate a virtual environment to isolate the project dependencies:
**python3 -m venv venv**
**source venv/bin/activate**

4. Install the project dependencies using pip:
**pip install -r requirements.txt**

5. Apply the database migrations:
**python manage.py migrate**

6. (Optional) Load sample data into the database:
**python manage.py loaddata sample_data.json**

7. Start the development server:
**python manage.py runserver**

8. Open a web browser and access the application at *http://localhost:8000.*

## Configuration
The Fire Reporting System uses the default SQLite database configuration provided by Django. If you wish to use a different database, you can update the settings in the settings.py file.

Additionally, you may want to modify other settings such as the secret key, email configuration, or allowed hosts. These settings can be found in the settings.py file as well.

## license.
The Fire Reporting System is open-source software released under the **MIT License.** Feel free to use, modify, and distribute the code as per the terms of the license.

## Contact
If you have any questions, issues, or suggestions regarding the Fire Reporting System, please contact project@example.com.
