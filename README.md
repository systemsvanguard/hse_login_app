# HSE Login Application

A web login and authentication app.  Back-end in Node.js with Express framework.  Front-end in React.js.  Authentication by the Passport.js library. Property of McMaster - HSE (Health Systems Evidence).

This application incorporates the following packages:

- axios
- bcryptjs
- jsonwebtoken
- mongoose
- passport
- react-router-dom
- validator 

## Steps to Install
- Use npm install -g nodemon , to get server restarts globally on your computer.
- git clone https://github.com/systemsvanguard/hse_login_app.git 
- npm install
- nodemon index.js OR node index.js 
- Runs on port 3000 --> http://localhost:3000/


## Installation

Use Yarn. See https://yarnpkg.com/en/ .   After cloning the repo, follow the steps below:
```sh
$ cd hse_login_app
```
```sh
$ yarn install
```
```sh
$ sudo mongod
```
```sh
$ yarn run dev
```

When editing the files, run the following command for webpack to watch your files and bundle whenever changes are made:
```sh
$ yarn run bundle
```

## Screenshots

Home Page before Login:

![Alt Home Page](http://ryanhunter.org/images/hse_home.png)

Sign up page:

![Alt Signup Page](http://ryanhunter.org/images/hse_signup.png)

Login page:

![Alt Login Page](http://ryanhunter.org/images/hse_login.png)

Dashboard which is only accessible after login:

![Alt Dashboard](http://ryanhunter.org/images/hse_dashboard.png)
