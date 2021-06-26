# Chit Chat Application

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)

## Introduction

A full Realtime Chat Application with Social Auth and dedicated chat APIs/sockets.

Firebase and Chat Engine are greats tools to setup apps fast and easily.

> ###### Special Thanks to `JavaScript Mastery` on Youtube for Providing some awesome tutorials.            

## Tech Stack

**Client:** React, Hooks, Chat Engine

**Server:** Firebase

**OAuth:** Google, Github

> ##### Note: Create a Firebase project & create a web app also social login oauth need to be create at google and github respectively.  
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`REACT_APP_CHAT_ENGINE_PROJECT_ID`

`REACT_APP_CHAT_ENGINE_SECRET_KEY`

`REACT_APP_FIREBASE_APP_KEY`

`REACT_APP_FIREBASE_AUTH_DOMAIN`

`REACT_APP_FIREBASE_PROJECT_ID`

`REACT_APP_FIREBASE_STORAGE_BUCKET`

`REACT_APP_FIREBASE_SENDER_ID`

`REACT_APP_FIREBASE_APP_ID`

Chat Engine ENV can be obtained from `https://chatengine.io/`

Firebase ENV can be obtained from `https://console.firebase.google.com/`

## Run Locally

Clone the project

```bash
  git clone https://github.com/Rezwanul-Haque/chit-chat.git
```

Go to the project directory

```bash
  cd chit-chat
```

Install dependencies

```bash
  yarn
```

Start the server

```bash
  yarn run start
```

## Feedback

If you have any feedback, please reach out to us at rezwanul.cse@gmail.com
