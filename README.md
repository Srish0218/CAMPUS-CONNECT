# CAMPUS-CONNECT


Welcome to the College Management System project developed using Python Django. This project aims to provide a comprehensive solution for managing student and staff information in a college setting. It includes features such as attendance management, result management, leave management, notifications, and feedback mechanisms.

## Features

### Admin Panel
- Manage courses, subjects, and sessions.
- Manage staff (teachers) and student records.
- Send notifications to staff and students.
- View attendance records of students.
- Manage leave applications from staff and students.
- Handle feedback from users.

### Staff Panel
- Manage exam results for students.
- Take and view attendance of students.
- Apply for leave.
- Receive notifications and provide feedback.

### Student Panel
- View and update personal profiles.
- View attendance records.
- Apply for leave and view leave history.
- Receive notifications and provide feedback.

### Additional Features
- Graphical representation of attendance data using graphs and pie charts.
- Clean and intuitive dashboard design for better user experience.
- Integration with Bootstrap CSS framework for UI elements.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/Srish0218/CAMPUS-CONNECT.git
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Make database migrations:
   ```
   python manage.py makemigrations
   python manage.py migrate
   ```

4. Create a superuser for admin access:
   ```
   python manage.py createsuperuser
   ```

5. Run the development server:
   ```
   python manage.py runserver
   ```

6. Access the application at http://localhost:8000/admin for the admin panel and http://localhost:8000/student or http://localhost:8000/staff for student and staff panels respectively.

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the contributors of Django and other open-source libraries used in this project.
# Campus-Connect
