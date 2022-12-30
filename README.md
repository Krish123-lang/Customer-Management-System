# Customer-Management-System
Customer Management System

Customer Management System is a **backend** project made with the help of Python Django Framework.

# What is Django?
### Django is a free and open-source web framework written in Python. It is designed to help developers take applications from concept to completion as quickly as possible. Django follows the model-template-view architectural pattern.

# What this project does?

This project stores customers information in a database. Admin has permission to do CRUD operations on customer. This project is secure against Cross site scripting (XSS), Cross site request forgery (CSRF), SQL injection, Clickjacking,etc.

This project helps admin to create, read, update, delete and filter customers information.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install django.

1. First of all create a isolated environment in your folder using following commands

```bash
i) virtualenv env
ii) env\scripts\activate

```

2. Then install tools using  

 ```python
 pip install -r requirements.txt
```

3. All of the packages needed in this project is installed 😀.
4. Then use

```python
 python manage.py makemigration
 python manage.py migrate
 python manage.py runserver
 ```

5. Copy the url(127.0.0.1:8000) and open it into your browser.
6. You must see this screen

![View All Employee](https://github.com/Krish123-lang/Employee-Management-System/blob/main/screenshots/view_all_employee.png)

7. Add an Employee
 ![Add an Employee](https://github.com/Krish123-lang/Employee-Management-System/blob/main/screenshots/add_employee.png)
 
8. Filter using name 
![Filter using name](https://github.com/Krish123-lang/Employee-Management-System/blob/main/screenshots/using_keyword_to_filter.png)

9. Filter Reults
![Filter results](https://github.com/Krish123-lang/Employee-Management-System/blob/main/screenshots/filter_results.png)

10. Remove Employee
![Remove Employee](https://github.com/Krish123-lang/Employee-Management-System/blob/main/screenshots/remove_employee.png)

> That's it have a great day :+1:  :shipit:
