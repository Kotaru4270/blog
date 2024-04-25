# BlogApp

[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A full-stack Blog post web application using [MongoDb](https://www.mongodb.com/, "Visit URL"), [Node](https://nodejs.dev/, "Visit URL") with [Expressjs](https://expressjs.com/, "Visit URL")

### Dependencies

- `body-parser`
- `express`
- `express-sanitizer`
- `ejs`
- `dotenv`
- `mongoose`
- `method-override`

---

## How to run the application?

**Install Dependencies**

```bash
    -> npm install
    OR
    -> npm i
```

**To Start the Development server :**

```bash
 npm run dev
```

**To Start the Production server :**

```bash
npm run start
```

---

## Connecting to the DataBase Using MongoDB

- Make sure latest version of **dotenv** Module is installed.
- Create a **.env** file.
- For setting up a local MongoDb DataBase
  - Mongo must be locally installed on your system.
  - Add to **.env**,
    - localDBURL='`mongodb://localhost:27017/Blogapp`'
- For setting up a Cloud Database Using Atlas, Add to **.env**
  - cloudDBURL='`mongodb+srv://<EnterMongoDBAtlas_UserName>:<EnterMongoDBAtlas_Password>@cluster0.c1tnc.mongodb.net/myFirstDatabase?retryWrites=true&w=majority`'

---

[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/open-source.svg)](https://forthebadge.com)
