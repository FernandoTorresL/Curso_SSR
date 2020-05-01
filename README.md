# Project: PlatziVideo (Curso Server Side Render con Express, Platzi, 2020)
### Proyecto de la EscuelaJS de Platzi México

## Description

### Implement SSR(Server Side Render) on PlatziVideo Project

This project begins by cloning another repo.

We take the finish project at this [repository: platzi/PlatziVideo](https://github.com/platzi/PlatziVideo), but using the branch: feature/router-redux
This can be done following the steps on section Installation (see that section below).

This is the result with **SSR**:

![Imgur](https://i.imgur.com/eOJdXWh.png)

---

## Installation. How I started to work with  this project ##

### Clone this repo
You can use and change *<my_folder>* on this instruction to create a new folder 
```
	git clone --single-branch -branch feature/router-redux git@github.com:platzi/PlatziVideo.git <my_folder>
```

### Change to working directory and install
```
	cd <my_folder>
	npm install
```

#### WIP, branch *feature/server-side-render-2020*
Here we created the branch *feature/server-side-render-2020* to work with this project and add:

- Install SASS, FileLoader.
- Use of Nodemon and Dotenv.
- Integrating Webpack with Express.
- Using React with Express
- Integrating react-router-config(React Router)
- Fix ESLint errors.

At the end, we created the branch **_develop_** and merge it with branch **_feature/server-side-render-2020_**

Create the branch **_release-1.0_** and integrated with **master**

---
## To be continued....
**This is a _WIP_ project that continues in another course and repo (I will defined later)**

------

## How to view this project

### Clone this repo
You can use and change *_<my_folder>_* on this instruction to create a new folder
```
git clone git@github.com:FernandoTorresL/Curso_SSR.git <my_folder>
```

### Change to working directory and install
```
cd <my_folder>
npm install
```

### Compile (optional)
```
npm run build
```

### Create .env file (only .env.example on github)
```
vi .env
```
Using **_.env.example_** file, you can copy the instructions there and paste them on **_.env_** file like this:
```
ENV=development
PORT=3001
```
you can change the port, of course!


### Start fake API
Start the json server to simulate an API for this project.
```
json-server initialState.json
```
You can see the data [here](http://localhost:3000/initialState)

### Execute
Now, open a new terminal, in the same folder, and execute with
```
npm run start:dev
```

Finally, you can view the project on [localhost:<your_port>](http://localhost:3001/)
Remember that you must use the same port that you define on your **_.env_** file

------

#### Follow me 
[fertorresmx.dev](http://fertorresmx.dev/)
[fertorresmx.com](http://fertorresmx.com/)

#### :globe_with_meridians: Twitter, Instagram: @fertorresmx