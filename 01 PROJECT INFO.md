
**# Instructions**

**For Admin Login Credentials, please create one using superuser!**
Got it! Here are the steps you need to follow:

1. **Install Requirements**: Run the following command to install the required packages listed in `requirements.txt`:
   ```
   pip install -r requirements.txt
   ```

2. **Database Migrations**: Make database migrations using the following commands:
   ```
   python manage.py makemigrations
   python manage.py migrate
   ```

3. **Create Superuser**: Create an admin superuser account by running the following command and following the prompts:
   ```
   python manage.py createsuperuser
   ```
   You'll be prompted to enter a username, email, and password for the superuser account.

4. **Run the Application**: Finally, start the application by running the following command:
   ```
   python manage.py runserver
   ```

After completing these steps, your application should be up and running. You can access the admin interface using the credentials you created for the superuser account.