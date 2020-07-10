# Server Side Render Course with Express, Platzi

## (Curso Server Side Render con Express, Platzi, version 2020)

### Part of PlatziVideo Project

PlatziVideo Project is the final project on EscuelaJS, Platzi, México and has several previous parts:

- Curso de Frontend Developer
- Curso Práctico de React
- Curso de React Router y Redux
- Curso de Server Side Render con Express (this repo)
- and more...

### Description

Implement SSR (Server Side Render) on PlatziVideo Project using:

- Babel, ESLint
- Nodemon, Dotenv
- Express (Node.js)
- React.js
- Webpack (cacheGroups, vendor files)
- Build optimizations

Here we created several branches using GitFlow method and integrated all on develop, then finally create **_release-1.1_** branch and integrated to **master** branch.

Some of the features that were implemented here:

- Install SASS, FileLoader
- Use of Nodemon and Dotenv
- Integrating Webpack with Express
- Using React with Express
- Integrating react-router-config(React Router)
- Defining SSR
- Fix ESLint errors
- Preparing deploy

This project begins by cloning another repo.

We take the finish project at 'Curso de React Router y Redux' [repository: platzi/PlatziVideo](https://github.com/platzi/PlatziVideo), but using the branch: feature/router-redux
This can be done following the steps on section Installation (see that section below).

This is the result, like the previous repo but with Server Side Rendering:

![Imgur](https://i.imgur.com/eOJdXWh.png)

---

## Installation

How started to work/colaborate with this project:

### Clone this repo

You can use and change *<my_folder>* on this instruction to create a new folder

```cmd
git clone --single-branch -branch feature/router-redux git@github.com:platzi/PlatziVideo.git <my_folder>
```

### Change to working directory and install

```terminal
cd <my_folder>
npm install
```

---

### How to view this project

#### Clone this repo

You can use and change *_<my_folder>_* on this instruction to create a new folder

```cmd
git clone git@github.com:FernandoTorresL/Curso_SSR.git <my_folder>
```

#### Change to working directory and install

```cmd
cd <my_folder>
npm install
```

#### Compile (optional)

```cmd
npm run build
```

#### Create .env file (only .env.example on github)

```cmd
vi .env
```

Using **_.env.example_** file, you can copy the instructions there and paste them on **_.env_** file like this:

```cmd
ENV=development
PORT=3001
```

you can change the port, of course!

#### Execute

Now, open a new terminal, in the same folder, and execute with

```cmd
npm run start:dev
```

Finally, you can view the project on [localhost:<your_port>](http://localhost:3001/)
Remember that you must use the same port that you define on your **_.env_** file

---

## Follow me

### [fertorresmx.dev](https://www.fertorresmx.dev/)

#### :globe_with_meridians: Twitter, Instagram: [@fertorresmx](http://www.twitter/fertorresmx)
