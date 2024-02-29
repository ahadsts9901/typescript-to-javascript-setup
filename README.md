## Here is how you can setup typescript and convert it to javascript

### Install Typescript globally

    npm i --global typescript

### Run these command

    tsc -init
    npm init -y

### Create two folders named "src" and "dist"

- src
- dist

### Create index.ts in src and index.js in dist

- src - index.ts
- dist - index.js

### Search "outDir" in tsconfig.json , unComment and replace it with this

    "outDir": "./dist",

### Run this command

    tsc -w

Now you write your code in typescript file and it will automaticallty convert to javascript in dist/index.js file

### Show some ❤️ by giving a ⭐
