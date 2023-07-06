# My Tailwind Boilerplate using PostCSS Project

This is the README file for my project.

## Usage

1. npm init -y

2. npm install -D tailwindcss postcss autoprefixer vite

3. npx tailwindcss init -p

4. 

/*tailwind.config.js  file*/

/** @type {import('tailwindcss').Config} */ <br>
module.exports = { <br>
  content: ['*'],//put '*'  in [] <br>
  theme: { <br>
    extend: {},<br>
  },<br>
  plugins: [],<br>
}<br>

5. In package.json file modified scripts value 

  "scripts": {
    "start": "vite"
  },

6. add css folder and create css file add three line of this in css file
 <ul>
    <li>@tailwind base;</li>
    <li>@tailwind components;</li>
    <li>@tailwind utilities;</li>
 </ul>

7. link css file in head tag of the html file

<link rel="stylesheet" href="css/main.css"> <br>

8. npm run start //we add vite so we command this <br>
this command provide a link <br>

9.

