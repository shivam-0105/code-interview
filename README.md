# code-interview

## About the project
A web application where in the user needs to create an account and profile and then the user and conduct interviews with realtime video call. It contains a normal text editor. All changes made in the editor are reflected on both side.

<img width="1470" alt="Screenshot 2024-08-20 at 1 21 07 PM" src="https://github.com/user-attachments/assets/675423b9-c43d-4ae4-9ad5-df4c4a446b19">



## Technologies Used 
1. ReactJS & TypeScript
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
<img width="1468" alt="Screenshot 2024-08-20 at 1 20 14 PM" src="https://github.com/user-attachments/assets/6a34281c-cc3f-43c7-ba55-b1558c97aba0">


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
