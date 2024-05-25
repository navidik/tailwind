this is how to use tailwindcss component to react project and make the ui so fast and easily

steps
npm create vite@latest my-project -- --template react   //this creating new vite react project 
cd my-project

npm install -D tailwindcss postcss autoprefixer //install the packages
npx tailwindcss init -p

and  "./index.html",  "./src/**/*.{js,ts,jsx,tsx}", put on tailwind.config.js content area

and put this 
@tailwind base;
@tailwind components;
@tailwind utilities; in index.css file

npm run dev

this is how install tailwindcss in react vite project

after that copy the component jsx file put to the project and create the ui
