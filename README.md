This project demonstrates a simple Flask-based REST API that performs basic CRUD (Create, Read, Update, Delete) operations. The application is containerized using Docker for easy deployment and environment consistency.

 📦 Features

- Create, Read, Update, and Delete users.
  
- RESTful API using Flask.
  
- Data stored using SQLite (or can be switched to PostgreSQL/MySQL).
  
- Dockerized for quick deployment.
  
- Compatible with Postman or any REST client for testing.

 🛠️ Project Structure

flask_crudop_api/
- app.py # Flask application with CRUD routes
  
- requirements.txt # Python dependencies
  
- Dockerfile # Image build instructions
  
- docker-compose.yml # Multi-container setup (optional)
  

 
🔍 API Endpoints
Method	Endpoint	Description
GET	/users	List all users
GET	/users/<id>	Get user by ID
POST	/users	Create a new user
PUT	/users/<id>	Update existing user
DELETE	/users/<id>	Delete user
Use Postman or cURL to interact with these endpoints.


🧪 Testing
Use the following sample JSON in Postman for creating a user:

json
Copy
Edit
{
  "name": "John Doe",
  "email": "john@example.com"
}


✅ Prerequisites
Python (only if running locally without Docker)
Docker
Docker Compose (optional)


🧾 License
This project is licensed under the MIT License.


🙋‍♂️ Author
Suhas S
GitHub: @Suhassszsz


