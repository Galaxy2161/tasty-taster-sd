# Restaurant app in React & Redux + Django
```bash
Restaurant App, with a frontend built in React & Redux and a backend built in Django API.
```
## Live Demo
Check out FRONTEND [LIVE DEMO](https://tasty-taster-frontend.netlify.app/) here!! Check out [API LIVE DEMO](https://backendapi-cooltees.onrender.com/api/) here!!
## Tech Used
* Frontend : React & Redux
* Backend : Django
## How to Install
1. Git Clone
```bash

```
2. Backend setting
```bash
cd backend/config
Python -m venv env
(For Mac) source env/bin/activate
(For Windows) env/Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
# Open http://127.0.0.1:8000/posts/
```
3. Frontend Setting
```bash
cd frontend/sd-frontend
npm install
npm start
# Open http://127.0.0.1:3000/
# in src open API.js change baseURl: http://127.0.0.1:8000/api/
```
