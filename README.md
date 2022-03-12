# code-interview

## About the project
A web application where in the user needs to create an account and profile and then the user and conduct interviews with realtime video call. It contains a normal text editor. All changes made in the editor are reflected on both side.

![Screenshot from 2022-03-12 19-37-34](https://user-images.githubusercontent.com/70219870/158021377-b21a32b3-c47b-4bc5-a5e7-b7b7577494b2.png)

## Host Link 
https://limitless-lowlands-12101.herokuapp.com/

## Technologies Used 
1. ReactJS
2. NodeJS
3. MongoDB
4. ExpressJS
5. SocketIO
6. PeerJS (for WebRTC)

## Features
- It has basic functionality like Register User, Login User, Delete User
- Create your entire profile, update your profile and delete your profile
- After profile, you can conduct interview calls
- It has a basic text editor for coding purpose (Implemented using SocketIO)
- It also has video call feature (Implemented using PeerJS) 

## Example
Interviewer  : [Gaurang Maheshwari](https://github.com/GaurangMaheshwari4) :laughing:
![Screenshot from 2022-03-12 19-20-28](https://user-images.githubusercontent.com/70219870/158021266-56a2e310-8389-48d2-9c0b-7d5297f43cb2.png)
![Screenshot from 2022-03-12 19-25-01](https://user-images.githubusercontent.com/70219870/158021355-f7037ca7-4efb-421e-bbaa-4a64be426f51.png)
![Screenshot from 2022-03-12 19-36-37](https://user-images.githubusercontent.com/70219870/158021357-23be4471-9cc9-4b19-9da9-78fd1791b47d.png)
![Screenshot from 2022-03-12 19-37-02](https://user-images.githubusercontent.com/70219870/158021361-5cf1c5ec-2bb9-435d-9ad7-6466f8d81eb1.png)
![Screenshot from 2022-03-12 19-37-07](https://user-images.githubusercontent.com/70219870/158021366-183ad18c-e0e4-4dd2-b7c0-59068eb1aebc.png)

## Install Locally
To get the app locally on your machine, follow the below mentioned steps
<br/>
Fork, then download or clone the repo.
```bash
git clone https://github.com/shivam-0105/code-interview.git
```
Now in the root directory, install the required backend dependencies using the following command in the terminal
```bash
npm install
```
Now for the frontend part, go to client folder and install the required dependencies
```bash
cd client
npm install
```
Now go back to root directory, then go to config folder, and create a file called "default.json"
```bash
cd config
```
In the *default.json* file, fill the following details
```bash
{
    "mongoURI": "MongoDB URL of your database",
    "jwtSecret": "You can type anything here",
    "githubClientId": "Go to Developer Settings of Github and then OAuth, and create an app and this will generate the clientID",
    "githubSecret": "Go to Developer Settings of Github and then OAuth, and create an app and this will generate the secretID"
}
```

## Contact Me
Mail Id : shivampanchal0105@gmail.com
<br />
LinkedIn : [Shivam Panchal](https://www.linkedin.com/in/shivam-panchal-3947391b0/)

Thank you for spending your precious time. Have a nice day :grin:
