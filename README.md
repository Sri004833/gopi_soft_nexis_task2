Task 2: Introduction to Python and Flask
📌 Objective

The objective of this task is to learn basic Python programming and build a simple web server using the Flask framework. This task introduces backend web development concepts and routing in Flask.

🛠️ Tools & Technologies Used

Python 3

Flask (Python Web Framework)

Visual Studio Code

Web Browser (Chrome / Edge)

GitHub for version control

📚 What I Learned

Python basics (variables, functions, loops)

What a web framework is

How Flask handles HTTP requests

Creating routes using decorators

Running a local development server

Serving different content for different URLs

📝 Steps Performed
1️⃣ Learn Python Basics

Understood variables, functions, and control statements

Learned how Python scripts are executed

2️⃣ Install Flask

Installed Flask using pip:

pip install flask

3️⃣ Create a Basic Flask Application

Created a file named app.py

Initialized the Flask application

Defined routes using @app.route()

4️⃣ Add Routes for Different URLs

/ → Home page

/about → About page

Each route returns different HTML content.

5️⃣ Run the Flask Server

Executed the application using:

python app.py


Accessed the application in the browser at:

http://127.0.0.1:5000/
http://127.0.0.1:5000/about

💻 Flask Application Code
from flask import Flask

app = Flask(__name__)

@app.route('/')
def home():
    return "<h1>Welcome to My Flask App!</h1><p>This is the home page.</p>"

@app.route('/about')
def about():
    return "<h1>About Us</h1><p>Learn more about our company.</p>"

if __name__ == '__main__':
    app.run(debug=True)

📁 Project Structure
Task-2/
│
├── app.py
├── templates/
├── Screenshot 2026-02-03 120022.png
├── Screenshot 2026-02-03 120039.png
└── README.md

✅ Expected Output

A running Flask web server

Home page displayed at /

About page displayed at /about

Different content rendered for different URLs

🎯 Conclusion

This task helped in understanding the fundamentals of Python backend development using Flask. It demonstrated how web servers work and how routing enables multiple pages in a web application.
