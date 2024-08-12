# Live Deployed Link :-
https://bit.ly/3AhimHM


# DEMO VIDEO :-
 https://www.loom.com/share/8afb7c80ce08425a86838be87197bc71?sid=b702439e-e11f-473a-b5d5-8119018fa711 


## To set up and run this project on your local machine, follow these steps:


To install and run this project on your local machine, follow these steps:

1. Clone repository
   ```
   git clone https://github.com/vishalyd05/ReachInbox-Assignment.git
   ```
2. Run Command:
   ```
   npm install
   ```
3. Run on localhost
   ```
   npm run dev
   ```
4. The app run on 'https://localhost:3000'


# implementation choices

# React + TypeScript + Vite
This template offers a basic setup to get React up and running in Vite, complete with HMR and some preconfigured ESLint rules.

Currently, there are two official plugins you can use:

@vitejs/plugin-react: Utilizes Babel for Fast Refresh
@vitejs/plugin-react-swc: Leverages SWC for Fast Refresh
Enhancing the ESLint Configuration
For production-level applications, it’s recommended to update the ESLint configuration to enable type-aware linting rules:

Adjust the parserOptions at the top level like this:
js
Copy code
export default {
  // other settings...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json', './tsconfig.app.json'],
    tsconfigRootDir: __dirname,
  },
}
Swap out plugin:@typescript-eslint/recommended with plugin:@typescript-eslint/recommended-type-checked or plugin:@typescript-eslint/strict-type-checked
Optionally, you can add plugin:@typescript-eslint/stylistic-type-checked for additional stylistic linting
Install eslint-plugin-react and include plugin:react/recommended and plugin:react/jsx-runtime in your extends list
This way, your project will have a more robust and type-safe linting configuration.









