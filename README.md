# MyBloggr-CRUD-Based-Blog-Web-App
MyBloggr is a CRUD Based Blog Web Application that provides a dynamic and 
interactive platform developed to facilitate content creation and engagement among users. 
The application utilizes Python Flask as its backend framework and HTML, CSS, and 
JavaScript for the frontend interface. The app data is stored in a SQLite database.

**<h1>Features:</h1>**
- User login and profile management
- Create and manage blogs
- Search users and blog posts
- Likes and comments support for blog posts
- Minimalist themed user-friendly interface

<h1>Instructions</h1>
<ol>
  <li>Clone repo</li>
  &nbsp&nbsp git clone "https://github.com/NishanthSamson/MyBloggr-CRUD-Based-Blog-Web-App"
  <li>Install dependencies using pip</li>
  &nbsp&nbsp pip install -r requirements.txt<br>
  <li>Run the flask application</li>
  &nbsp&nbsp python -m flask run app.py<br>
</ol>

<h3>Dependencies:</h3>

- flask_sqlalchemy - for ORM
- flask_login - for managing user authentication
- flask_wtf - to creat flask forms to collect data from the user
- werkzeug - to secure file uploads
- flask_bcrypt - for hashing support to store sensitive data
