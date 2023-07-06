# My Tailwind Boilerplate using PostCSS Project

This is the README file for my project.

## Usage

1. npm init -y

2. npm install -D tailwindcss postcss autoprefixer vite

3. npx tailwindcss init -p

4. 

/*tailwind.config.js  file*/

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ['*'],//put '*'  in []
  theme: {
    extend: {},
  },
  plugins: [],
}

5. In package.json file modified scripts value 

  "scripts": {
    "start": "vite"
  },

6. add css folder and create css file add three line of this in css file

@tailwind base;
@tailwind components;
@tailwind utilities;

7. link css file in head tag of the html file

<link rel="stylesheet" href="css/main.css">

8. npm run start //we add vite so we command this
this command provide a link

9.

