# WebinAR 

You might have come across various ads on the internet claiming to make web development easy. Well, in this project I made it a lot easier. You get to develop your own website using AR, which makes it simple, visual and interactive.

## Features! ⭐
- Create a unique design using the application and generate your HTML page.
- Provide a full interactive AR experience.
- Realtime HTML component using Bootstrap
- Since using Bootstrap components, you can easily generate responsive page.

## Step wise guide to get started with the project! 🐱‍👤

### Requirement 🔍
- ARCore supporetd phone 📱
- Unity 2018.4.27f1 *
- Node already setup 
- Git already setup 

### 1. Clone the project
Clone this git project by using below code, make sure your git is already configured in your machine. By cloing this project to will be able to use all the neccesary files already present in the project. Also after clone command run submodule update command to also get the submodules file.
```
>> git clone https://github.com/AmanBohra7/WebinAR.git
>> git submodule update --init
```
### 2. Run Express server
To run the express server we have do to go the path /WebinAR/WebinAR-React-App/backend dir. And will node to run the server on local host.
```
>> cd /WebinAR/WebinAR-React-App/backend
>> node server.js
```
### 3. Run React-app
Now we have to start the react app at path /WebinAR/WebinAR-React-App, which will be loaded up with some dummy html code initially ( you can go through the architecture the understand how it is started ). Before that we have install the node dependencies. 
```
>> cd ..
>> npm install
>> npm start
```
### 4. Open Unity
You are almost there..! Now you have to work on your favourite tool UNITY. Follow the bellow steps.
1. Connect your ARCore supperted phone via USB
2. Enable USB Debugging
3. Select transfer files mode (from charge only)
4. Open main_2 scene
### 5. Play/Test application
Now you can hit play button and test the application. ▶

## Look once over the demo video! 📽
<a href="https://www.youtube.com/watch?v=bl891ApqNfo" target="_blank"><img alt="mail" src="https://github.com/Faizun-Faria/Faizun-Faria/blob/main/Files/youtube.svg" title="Youtube" width="64" height="64" /></a>

## For Contributing
Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<br/>
*Currenty the project is working in Unity 2018.4.27f1 as the project is using ARCore SDK (Not integerated with ARFoundation). But in new updates it will be working on newer versions. 





