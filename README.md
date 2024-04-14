## Python-Django-Framework
#### 1. Model in django.
```text
In django, a model is a python class that represents a special type of data in the database.
It's act as an abstraction layer that allows developers to interact with the database using high-level pythonic syntax,
without having to write SQL queries directly.
```
#### 2. view in django.
```
In django, a view is a python function or class-based view that receives web requests from clients, processes them, and returns web responses.
It's the component responsible for handling the business logic of a web application.
View interect with models to retrive or manipulate data and templates to render HTML responses to users.
They serve as the intermediary between the user's request and the appropriate response.
```
#### 3. Templates in django.
```
In django, templates serve as the frontend presentation layer of web applications.
they are HTML files with embedded Django Templates language (DTL) code. Templates play a vital
role in separating the logic of a web application from it's presentation, promoting clean and\
maintainable code architecture.
```
#### 4. init.py in django.
```
it’s an empty Python file. It is called when the package or one of its modules is imported.
This file tells the python interpreter that this directory is a package and that the presence of the __init.py__ file makes
it a python project. 
```
#### 5. setting.py in django.
```
It holds all the configuration values that your web app needs to work.
ex. pre-installed, apps, middleware, default database, API keys,and buch of other stuff.
```
#### 6. URLs in django.
```
When a user visits a given URL route in the browser, the URLs in the urls.py file are compared.
The user then receives the response for the requested URL after retrieving a corresponding view method.
```
#### 7. Cookies and sessions in django.
```
Cookies and sessions are both essential components in web development for managing user data and maintaining state.
While cookies are stored on the client-side and are used for tasks such as user identification and preference storage,
sessions are stored on the server-side and are used for storing more sensitive user data.
```
#### 8. Django ORM.
```
Object-Relational Mapping (ORM) in Django is a technique that enables developers to interact with
databases using Python objects instead of SQL queries.
```




