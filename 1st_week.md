Week1:Getting Started with REACT

Embarking on my React journey, I eagerly embraced the challenges of my first week diving into the world of React.

Installation and setup in Ubuntu

I began with installing React for setting up my development environment in linux. Following the React documentation,I implemented the provided code snippets. ##Introduction REACT At the time of writing, it’s the one of the most popular Javascript library for developing user interfaces.

step1:Install Node.js using NVM
```
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.39.0/install.sh 
source ~/.profile
```
OR for the latest thing: You can always go through the official https://github.com/nvm-sh/nvm

step2:Install Node.js
```
nvm install v21.1.0
```

step3:Install react-app
```
sudo npm -g install create-react-app
create-react-app --version
```

Step4: Create & Launch First React Application

```
create-react-app rak-app
cd rak-app
npm start
```

Fire up your browser and browse your server’s IP address
http://server-ip:3000