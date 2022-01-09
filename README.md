# API-Dev-Readme

# Python-API-Dev

This is the minor project for the API development in Python Language and uses below tools to create this project
FastAPI - A web framework for building APIs with Python
SQLAlchemy - Python SQL toolkit and Object Relational Mapper
Alembic -  Lightweight database migration tool for usage with the SQLAlchemy Database
SQL - PostgreSQL

This project is a prototype for managing posts using API with the functions of create post, delete, update, get all post details, get post by ID, like/dislike post using vote mechanism. The post will only be maintained after creating a user(if not exist) or by login.

FastAPI Swagger Link: https://fastapi-shubham.herokuapp.com/docs

How To Use:
1. Create a User(Only required for the first time) using email, password and phone_number. Save your id to get your details in future. 
2. At the top-right page click on Authorize button and type email and password. Click on Authenticate. Only correct email and password will work.
3. After login you can create post using required information like title of the post, content and if it is published or not.
4. Post can be Liked or disliked under Vote section and any logged-in user can like or dislike the post. Type the id of the post you want to like and if you want to like the post    type 1 in the "dir", and if you want to dislike the post you can type 0 in front of "dir". Post will only disliked if the post is already liked by the logged-in user.
4. Update will work by specifying the Id of the post for which you want to update.
5. Delete the post. Delete post will only work for the actual user who has created the post.

This project is with the limited functionality and just for the demo purpose.
