# social_media_backend

https://user-images.githubusercontent.com/88747336/201050421-6ace17c4-1411-48f1-ae2a-4bb6c33dd1e9.mp4

# Goals

Goal of this project is to make a user to able to create posts and update their profile information. The main go file first initializes a server client over HTTP and sends a 200 ok with a JSON payload once created. The main.go file calls the database to create and write to the database file in the internal directory. The user on the other end has the option of creating a profile and a post once they have explored the application. The internal/database file houses the methods needed to create, update, and delete user profiles and posts, given some credentials. Unit tests were created to test invalid profile creation and update requests.

# Installation
Download from the github repository

### go install github.com/elwinjoshua/social_media_backend/internal/database
