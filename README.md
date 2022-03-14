# React README Quiz!

<div>
  <img alt="react" style="background-color: black" src="https://betabeers.com/static/uploads/blog/20170420_React_logo_wordmark.png" />
</div>

## Instructions

- `Fork` and `clone` this repository
- You will be answering the quiz questions below by editing this README with your answers
- Give the best explanation you can for each question in **your own words**
- React Docs: https://reactjs.org/docs/getting-started.html#learn-react

### 1. How do you create a React App from the terminal command line?

```sh
You type the following command to your terminal: npx create-react-app my-app
cd my-app
```

### 2. If you clone a React App that has already been created, what command is needed to start developing with its dependencies?

```sh
I’m not sure if I understand this question correctly but you run "npm install" to install dependencies
```

### 3. How do you start the in-browser development server for a React App?

```sh
You type 'npm start' in your terminal
```

### 4. What folder in a React App should component files be created in?

```sh
In 'src' folder you can make a 'components' folder and create them there.
```

### 5. What is the syntax for a function based component?

```sh
import React from 'react’;

function App() {
const hello = 'Hello There!';

return <h1>{hello}</h1>;
}

export default App;
```

### 6. What direction are props passed in a React Component?

```sh
They are passed from parent to child components down the component tree.
```

### 7. How is a React Component accessed in another file?

```sh
First you need to export the component by using 'export default' then component name, and then you import it by using 'import from' and the path. For example: import Button from './components/Button'
```

### 8. How do we gain access to props in a child component?

```sh
In function components, we access the props in child component through the first function argument. const MyProps = (props) => {
  const myporps = props.myprops;
