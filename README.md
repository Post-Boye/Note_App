The note-taking app was developed to provide a user-friendly platform for capturing and organizing thoughts.
Key features included note creation, organization, and responsive design. Real-time updates and scalable database operations improved collaboration. 
User authentication and authorization mechanisms ensured data privacy. Future enhancements include categorization, search, and collaboration options.
The app's success is attributed to its functionality, lessons learned, and commitment to continuous improvement.
The app remains dedicated to evolving with new technologies and user needs.
## You need:
- Database (MongoDB)
- Google Console Account to create the API Auth Key's

## Create .env file
Create a .env file to store your credentials. Example below:

```
MONGODB_URI = mongodb+srv://<username>:<password>@mongodburlhere
GOOGLE_CLIENT_ID= YOUR_GOOGLE_ID_HERE
GOOGLE_CLIENT_SECRET= YOUR_GOOGLE_CLIENT_SECRET_HERE
GOOGLE_CALLBACK_URL=http://localhost:5000/google/callback
```

## Installation
To install and run this project - install dependencies using npm and then start your server:

```
$ npm install
$ npm start
