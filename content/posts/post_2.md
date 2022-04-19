---
title: "Mi ruta de aprendizaje en LaunchX"
date: 2022-04-05
description: 'En este post explicaré como hacer proyectos de JS'
---

Hola! En este post quiero contarte como poner a andar un proyecto en JS:
-Primero crea una carpeta donde vas a guardar tu proyecto
-Con la terminal poner el comando: npm init ->Te creará un package.json
-Si se desean utilizar test: npm install --save-dev jest ->Te creará una carpeta node_modules 
-Para poder correr se usa: npm start -> Para poder usarla se necesita crear una ruta en package.json: "start": "node index.js"
-Para realizar los test se usa: npm test -> Se necesita poner en package.json "test": "node ./node_modules/.bin/jest" para MAC
 O "test": "node --experimental-vm-modules ./node_modules/jest/bin/jest.js"
Gracias poer leer, nos vemos en el próximo post.
