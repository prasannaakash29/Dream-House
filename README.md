# Dream House
  This is an e-commerce website where you can buy, sell, lease, or rent properties. You can sign up/sign in to use the website and easily search for properties using the location, prices, and other aspects while looking for the perfect place! Detailed information about all the listed properties is provided along with verified images for easy navigation and your safety. 

# Dream House in React & Redux + Django
```
Dream House, with a frontend built in React & Redux and a backend built in Django API.
```
## Live Demo
**This App uses a Heroku free plan, so I am afraid that it takes time to load the pages.**
Check out [FRONTEND LIVE DEMO](https://frontend-dreamhouse.herokuapp.com/) here!!
Check out [API LIVE DEMO](https://backend-dreamhouse.herokuapp.com/) here!!
## Tech used
```
* Frontend : React & Redux
* Backend : Django
```
## How to Install
1. Git Clone
```
git clone https://github.com/DreamHouseProject1/DreamHouse
```
2. Backend setting
```
cd backend
Python -m venv env
(For Mac) source env/bin/activate
(For Windows) env/Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
# Open http://127.0.0.1:8000/posts/
# To have dummy data for testing run:
python manage.py fixtures/dummy-data.json
```
3. Frontend setting
```
cd frontend
npm install
npm start
# Open http://127.0.0.1:3000/
```
