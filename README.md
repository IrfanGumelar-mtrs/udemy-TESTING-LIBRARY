# React Testing Example

---

### Legal

##### Credits

This repository is forked from [Bonnie Schulkin's
](https://github.com/bonnie) repository that originally was for her Udemy Course [React Testing Library and Jest](https://www.udemy.com/course/react-testing-library/?referralCode=0B60E8FEB40F0D159E84).

##### Changes made to the original code

- `readme.md` is altered to add legal information, introduction and instruction how to run the app. And the title is renamed to **_"React Testing Example"_**
- `sundaes-on-demands` directory is moved to the root directory and renamed to `frontend` directory
- `sundae-server` is renamed to `backend` directory
- Files and directories that not part of `sundes-on-demands` and `sundae-server` is removed.

---

### Introduction

This app is a simple ice cream order application to demonstrate how to do testing on React application.

This repository consist of 2 subs repository which is frontend repository under `frontend` directory and backend repository under `backend` directory.

The frontend directory is for the React app and the backend directory for the Express app.

### How to run the app

Run the frontend app. From your app root direcotry:

```
cd frontend
npm install
npm run start
```

Run the backend app. From your app root directory:

```
cd backend
npm install
npm run start
```

### How to run the test

From your app root directory:

```
cd frontend
npm install
npm run test
```
