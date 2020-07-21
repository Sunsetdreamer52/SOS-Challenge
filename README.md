# Student 2 Student Web Application

A way for student to connect with other students/tutors and get help with homework easily.

This application supports the  is hosted on the Heroku Cloud Application Platform. You can [Visit our Website](https://sos-test-app.herokuapp.com/) here or create your own Heroku Cloud application from our repository below.

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Running Locally

Make sure you have [Git](https://git-scm.com/downloads), [Microsoft Visual Studio Code](https://code.visualstudio.com/) (or another tex editor), and the [Java SE Development Kit 8](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html) Installed on your PC.

```sh
1. Install Git
2. Install Visual Studio Code (VSC)
3. Open VSC and push ctrl+shift+p on your keyboard
4. Now Type "Git:Clone"
5. Paste our respositor link  
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

If you're going to use a database, ensure you have a local `.env` file that reads something like this:

```
JDBC_DATABASE_URL=jdbc:postgresql://localhost:5432/java_database_name
```

## Deploying to Heroku

```sh
$ heroku create
$ git push heroku master
$ heroku open
```

## Documentation

For more information about using Java on Heroku, see these Dev Center articles:

- [Java on Heroku](https://devcenter.heroku.com/categories/java)
