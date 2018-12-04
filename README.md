# react-mobx-firebase-authentication

[![Build Status](https://travis-ci.org/the-road-to-react-with-firebase/react-mobx-firebase-authentication.svg?branch=master)](https://travis-ci.org/the-road-to-react-with-firebase/react-mobx-firebase-authentication) [![Slack](https://slack-the-road-to-learn-react.wieruch.com/badge.svg)](https://slack-the-road-to-learn-react.wieruch.com/) [![Greenkeeper badge](https://badges.greenkeeper.io/the-road-to-react-with-firebase/react-mobx-firebase-authentication.svg)](https://greenkeeper.io/)

* [React + Firebase Tutorial](https://www.robinwieruch.de/complete-firebase-authentication-react-tutorial/)
* [React + Firebase + Redux Tutorial](https://www.robinwieruch.de/react-firebase-mobx-tutorial)
* [Live Version of half of the Tutorial](https://react-mobx-firebase-authentication.wieruch.com/)

## Features

* uses:
  * only React (create-react-app)
  * firebase 5
  * react-router 4
  * **mobx**
* features:
  * Sign In
  * Sign Up
  * Sign Out
  * Password Forget
  * Password Change
  * Verification Email
  * Protected Routes with Authorization
  * Roles-based Authorization
  * Social Logins with Google, Facebook and Twitter
  * Linking of Social Logins on Account dashboard
  * Auth Persistence with Local Storage
  * Database with Users and Messages

## Installation

* `git clone git@github.com:the-road-to-react-with-firebase/react-mobx-firebase-authentication.git`
* `cd react-mobx-firebase-authentication`
* `npm install`
* `npm start`
* visit http://localhost:3000/
* Use your own Firebase Credentials

### Use your own Firebase Credentials

* visit https://firebase.google.com and create a Firebase App
* copy and paste your Credentials from your Firebase App into *src/components/Firebase/firebase.js* file or in .env file
* activate Email/Password, Google, Facebook and Twitter Sign-In Methods for your Firebase App
