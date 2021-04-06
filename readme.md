# Purpose

I have created and developed this very simple project for purpose of learning ReactJs.

For overview you can go: https://movie-rental-ui-myg.herokuapp.com/

**Note:** The sample website may open slowly due to deployed on free tier option of Heroku and MongoDb. It takes approximately 15 seconds to see the datas.

Demo credential

> username: demo@demo.com password: demodemo

Admin credential

> username: admin@admin.com password: admin

# Used Technologies and Environments

- **Frontend** : ReactJs v17
- **Backend** : NodeJs, ExpressJs v4
- **Database** : MongoDb
- **Additional libraries** : lodash v4, jsonwebtoken v8, react-toastify v7, query-string v6, jwt-decode v3, joi v17, bootstrap v5, axios v0.21
- **Frontend Deployment Environment** : https://www.heroku.com/
- **Backend Deployment Environment** : https://www.heroku.com/
- **Database Deployment Environment** : https://cloud.mongodb.com/v2

## Setup

Make sure to follow all these steps exactly as explained below. Do not miss any steps or you won't be able to run this application.

### Install MongoDB

To run this project, you need to install the latest version of MongoDB Community Edition first.

https://docs.mongodb.com/manual/installation/

Once you install MongoDB, make sure it's running.

### Install the Dependencies

Next, from the project folder, install the dependencies:

    npm i

### Populate the Database

    node seed.js

### Run the Tests

You're almost done! Run the tests to make sure everything is working:

    npm test

All tests should pass.

### Start the Server

    node index.js

This will launch the Node server on port 3900. If that port is busy, you can set a different point in config/default.json.

Open up your browser and head over to:

http://localhost:3900/api/genres

You should see the list of genres. That confirms that you have set up everything successfully.
