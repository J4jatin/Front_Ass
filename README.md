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

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md): Utilizes [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc): Leverages [SWC](https://swc.rs/) for Fast Refresh

## Enhancing the ESLint Configuration

For production-level applications, it’s recommended to update the ESLint configuration to enable type-aware linting rules:

1. **Adjust the `parserOptions` at the top level:**

    ```javascript
    export default {
      // other settings...
      parserOptions: {
        ecmaVersion: 'latest',
        sourceType: 'module',
        project: ['./tsconfig.json', './tsconfig.node.json', './tsconfig.app.json'],
        tsconfigRootDir: __dirname,
      },
    }
    ```

2. **Swap out the recommended ESLint plugin:**

    - Replace `plugin:@typescript-eslint/recommended` with:
      - `plugin:@typescript-eslint/recommended-type-checked`
      - or `plugin:@typescript-eslint/strict-type-checked`
    
3. **Optionally, add stylistic linting:**

    - Include `plugin:@typescript-eslint/stylistic-type-checked` if desired.

4. **Install and configure React ESLint plugin:**

    - Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and include:
      - `plugin:react/recommended`
      - `plugin:react/jsx-runtime` in your `extends` list.

By following these steps, your project will benefit from a more robust and type-safe linting configuration.









