# Create a basic calculator component
In this activity you will create a `Calculator` component that can be customized through props to display arithmetic operations.

## Getting started
In order to get started, run `npm install` from within this folder to get all the dependencies installed. Once you've completed installation of all the dependencies, run `npm run dev` to start the development server.

## Your challenge
Create a React component named `Calculator` that receives the following props:
- `a`: Number
- `b`: Number
- `operator`: It can be one of the following values `+`, `-`, `*` and `/`.

The component will display an arithmetic operation based on the params received with the following format: `a operator b = z`, where `a` is the value of the `a` param, `b` is the value of the `b` param, `operator` is the value of the `operator` param, and `z` is the result of performing the respective operation between `a` and `b`:

Examples:

- `<Calculator a={2} b={3} operator="+" />`  should render `2 + 3 = 5`
- `<Calculator a={5} b={2} operator="-" />`  should render `5 - 2 = 3`
- `<Calculator a={10} b={4} operator="*" />`  should render `10 * 4 = 40`
- `<Calculator a={20} b={4} operator="/" />`  should render `20 / 4 = 5`

##  Bonus challenge
- The component should render `Error: Invalid params` if either `a` or `b` are not numbers.
- The component should render `Error: Invalid params` if either `operator` is `/` and `b` is `0`.

## Tips and best practices
- Components should live inside a `components` folder.
- Each component should have its own file with the file name matching the component's name


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
