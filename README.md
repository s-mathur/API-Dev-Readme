# API-Development Readme

This is the minor project for the API development in Python Language and uses the below tools to create this project
FastAPI - A web framework for building APIs with Python
SQLAlchemy - Python SQL toolkit and Object Relational Mapper
Alembic -  Lightweight database migration tool for usage with the SQLAlchemy Database
SQL - PostgreSQL

This project is a prototype for managing posts using API with the functions of creating the posts, deleting, updating, getting all post details, getting posts by ID, like/dislike posts using vote mechanism. The post will only be managed after creating a user(if not exist) or by logging in using email and password.

FastAPI Swagger Link: https://fastapi-shubham.herokuapp.com/docs

How To Use:
1. Create a User(Only required for the first time) using email, password, and phone_number. Save your id to get your details in the future. 
2. At the top-right page click on Authorize button and type email and password. Click on Authenticate. Only the correct email and password will work.
3. After login you can create a post using required information like the title of the post, content, and if it is published or not.
4. Post can be Liked or disliked under the Vote section and any logged-in user can like or dislike the post. Type the id of the post you want to like and if you want to like the post type 1 in the "dir", and if you want to dislike the post you can type 0 in front of "dir". The Post will only be disliked if the post is already liked by the logged-in user.
4. Update will work by specifying the Id of the post for which you want to update.
5. Delete the post. Delete post will only work for the actual user who has created the post.

This project is with limited functionality and is just for demo purpose.
