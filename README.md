<p align="center">
    <a href="https://www.udemy.com/course/understanding-typescript/learn/lecture/16950324#overview" target="blank"><img src="https://logodownload.org/wp-content/uploads/2019/07/udemy-logo-0.png" width="120" alt="Udemy Logo" /></a>
</p>

<p align="center"><a href="https://www.typescriptlang.org/" target="_blank">Typescript</a> exercise to learn how to properly use Node.js/Express with Typescript.</p>

<p align="center">
    <a href="#" target="_blank"><img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" /></a>
    <a href="#" target="_blank"><img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge" alt="Express.js" /></a>
    <a href="#" target="_blank"><img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" /></a>
</p>

## Getting started

```shell
# In a first shell
npm install   # install the dependencies
npm start     # start the local server with live reload (open a new browser tab)

# In another shell
npm run compile:watch
```

## How does it work

The `src/app.ts` file starts the local server. It opens routes of the API and waits for requests.
When a request is send to the API, the router triggers the controller function dedicated to the target route.
The controller performs the get/create/update/delete operation and then respond a JSON message to the API.

## Credits

[Credits to Maximilian Schwarzmüller / Udemy](https://www.udemy.com/course/understanding-typescript/learn/lecture/16998826#overview)
