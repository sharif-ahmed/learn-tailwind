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

5. In package.json file modified scripts value  <br>

  "scripts": { <br>
    "start": "vite" <br>
  }, <br>

6. add css folder and create css file add three line of this in css file <br>
  @tailwind base; <br>
  @tailwind components; <br>
  @tailwind utilities; <br>


7. link css file in head tag of the html file <br>

<link rel="stylesheet" href="css/main.css"> <br>

8. npm run start //we add vite so we command this <br>
this command provide a link <br>

9.

