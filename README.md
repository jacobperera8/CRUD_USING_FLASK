# How to execute the application 

First install the python interpreter within the project.

1. Create virtual Environment 
"python3 -m venv venv"

2. Activate Virtual Environment
"source venv/bin/activate"

3. # Endpoints

    http://localhost:5000/api/users (Get all users in database) (GET)
    
    
    http://localhost:5000/api/users/<user_id> (Get user by ID) (GET)
    
    
    http://localhost:5000/api/users/add (Add a user to the database) (POST)
    
    
    http://localhost:5000/api/users/update (Update user record) (PUT)
    
    
    http://localhost:5000/api/users/delete/<user_id> (Delete user record) (DELETE)

