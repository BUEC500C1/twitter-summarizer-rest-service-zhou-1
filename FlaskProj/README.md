# Flask    
Flask is a lightweight WSGI (Web Server Gateway Interface) web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications.    

## Install Flask   
Install and update using pip:    
```
pip install -U Flask
```

## How to run file in Flask    
run simpFlask program:   
```
python simpFlask.py    
```
Then on shell, use below command:   
```
$ env FLASK_APP=simpFlask.py flask run
 * Serving Flask app "simpFlask.py"
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: off
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```

# Flask-RESTful     
Flask-RESTful is an extension for Flask that adds support for quickly building REST APIs. It is a lightweight abstraction that works with your existing ORM/libraries.     

## Install Flask-RESTful   
Install Flask-RESTful with pip    
```
pip install flask-restful
```

## How to run file with Flask-RESTful   
run simpFlaskRESTful program:   
```
python simpFlaskRESTful.py
 * Serving Flask app "simpFlaskRESTful" (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: off
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
127.0.0.1 - - [29/Feb/2020 16:14:11] "GET / HTTP/1.1" 200 -
```
Now open up a new prompt to test out your API using curl:     
```
$ curl http://127.0.0.1:5000/
{"hello": "world"}
```














