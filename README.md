# Django-School-Management-System

This app is meant to be used by school manager to manage their school records:
 - student data
 - staff
 - results and
 - finances.

It currently doesn't allow students/staff to login.

## 🚀 Getting Started

Follow these steps to run the project locally:

## 1️⃣ Clone the Repository


```bash
git clone https://github.com/Abhay-Dwivedi2002/School-Management-System.git

cd tourtravels
```


## 2️⃣ Create Virtual Environment

```bash
python -m venv env
```


## 3️⃣ Activate Virtual Environment

Windows:

```bash
env\Scripts\activate
```

Mac/Linux:

```bash
source env/bin/activate
```


## 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```


## 5️⃣ Run Migrations

```bash
python manage.py migrate
```


## 6️⃣ Start the Development Server

```bash
python manage.py runserver
```


## 7️⃣ Open in Browser

```bash
http://127.0.0.1:8000/
```


## Admin Login
When you run migrate, a superuser is created.
```bash
username: admin
password: admin123
```

## Coding Standards
```bash
isort .
black .
```

## Test
```bash
python manage.py test
```

## License
This project is created for learning purposes only.

##  Under development