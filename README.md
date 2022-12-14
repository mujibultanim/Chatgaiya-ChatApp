# Chatgaiya-ChatApp
A fullstack Messaging app which has all the basic features for a group,private chat, handy features like typing indicator and notification icon and encryption.
User can create unlimited group and private messages. anyway, this project was made for Semester project.

## Live App link
[Chatgaiya ChatApp](http://chatgaiya-chatapp.herokuapp.com)

## Main Features In Screenshots
### Log In
![](https://github.com/mujibultanim/Chatgaiya-ChatApp/blob/main/Demo/log%20in.png)
### Registration Page
![](https://github.com/mujibultanim/Chatgaiya-ChatApp/blob/main/Demo/registration.png)
### Group chat
![](https://github.com/mujibultanim/Chatgaiya-ChatApp/blob/main/Demo/groupchat.png)
### Notification and Search Bar & Private Chat
![](https://github.com/mujibultanim/Chatgaiya-ChatApp/blob/main/Demo/notification%20and%20search.png)
### Typing Indicator
![](https://github.com/mujibultanim/Chatgaiya-ChatApp/blob/main/Demo/typing%20indicator.png)


## Tech Used

**Client:** React JS

**Server:** Node JS, Express JS

**Database:** Mongo DB

<details> 
  <summary>How to run locally :point_down:</summary>
  
  >open terminal and go to the **Chatgaiya-ChatApp** directory.
>As for security reason, it's a common practice that no one upload their crusial credentials and dotenv file.
So, for using it,create a dotenv file in main directory(chatgaiya-chatapp/) and put essential references like,

```
  MONGO_URI=
  PORT=5000
  JWT_SECRET=mujib71
  NODE_ENV=production
```
 
 after equal sign paste your secret values without any spaces. As of now, you understood that you need to make a mongodb atlas account and a cluster for URI, if you're a beginner then you could use online help
  
**Clone the project**
  >before You proceed, you should have installed node in your machine
```
https://github.com/mujibultanim/Chatgaiya-ChatApp
```
**Go to the project folder**
```
cd Chatgaiya-Chatapp
```
**install dependencies:**
```
npm install
```

**Note: If you don't have yarn globally installed then install it**

```
cd frontend
yarn install
```
>now, build the project for production:
```
yarn build
```

**Start the server**
>just back one step to the main folder

```
cd ..
npm start
```
  </details>

**Enjoy...** :relaxed:

This project is youtube Tutorials inspired and made solely for Learning purposes not for any serious job.
