# project-sweep-fe

This repo contains the front-end for the app Aisle Navigate which is a progressive web app designed to help people with their shopping by letting them enter their shopping list, select their desired supermarket and then provides them with the most efficient path to go around the supermarket to do their shopping.

The App is hosted using Firebase at https://project-sweep-fe.web.app/ and interacts with a bespoke backend API which is hosted using Heroku at https://aisleonator.herokuapp.com/api/products. The backend repo can be found at https://github.com/benlee38b/project-sweep-be.

 ## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
In order to successfully run this repo on your local machine you will require node version v13.8.0

cloning & installing
To clone this repo run the below code:

```

git clone https://github.com/benlee38b/NC-News-FE

```

change directory into that repo and open the repo in your preferred code editor, then run:
```
npm install
```

to install dependencies for the app. Axios is being used for the HTTP requests due to the clear promised based structure of the requests, however another HTTP client could be used instead if desired.

#### Built With
React - Web Framework
