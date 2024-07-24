
# Online Course Application - IBM Django Project

### Set up Virtual Environment

```linux
pip install --upgrade distro-info
pip3 install --upgrade pip==23.2.1
pip install virtualenv
virtualenv djangoenv
source djangoenv/bin/activate
```

### Python runtime and Test template

```linux
pip install -U -r requirements.txt
```

### Migrations
```linux
python3 manage.py makemigrations
python3 manage.py migrate
```

### Run Server (Django admin and Django web server)
```linux
python3 manage.py runserver
```

### Create an admin user
```linux
python3 manage.py createsuperuser
```
**General Notes**

An `onlinecourse` app has already been provided in this repo upon which you will be adding a new assesement feature.

- If you want to develop the final project on Theia hosted by [IBM Developer Skills Network](https://labs.cognitiveclass.ai/), you will need to create the same project structure on Theia workspace and save it everytime you close the browser
- Or you could develop the final project locally by setting up your own Python runtime and IDE
- Hints for the final project are left on source code files
- You may choose any cloud platform for deployment (default is IBM Cloud Foundry)
- Depends on your deployment, you may choose any SQL database Django supported such as SQLite3, PostgreSQL, and MySQL (default is SQLite3)

**ER Diagram**
For your reference, we have prepared the ER diagram design for the new assesement feature.

![Onlinecourse ER Diagram](https://github.com/ibm-developer-skills-network/final-cloud-app-with-database/blob/master/static/media/course_images/onlinecourse_app_er.png)

**Project Screenshots**
![Screenshot 2024-07-25 011502](https://github.com/user-attachments/assets/c6bebbd1-09c0-43e6-b3af-0657aee5a530)
