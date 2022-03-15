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
In your desired repository preform npx create-react-app (Apps-Name)
```

### 2. If you clone a React App that has already been created, what command is needed to start developing with its dependencies?

```sh
npm install
```

### 3. How do you start the in-browser development server for a React App?

```sh
npm start
```

### 4. What folder in a React App should component files be created in?

```sh
In the src folder
```

### 5. What is the syntax for a function based component?

```sh
It has to have at least 4 things
import React from 'react';
function NameOfFunction() {
  return (
    <div>
    <div/>
  );
}
export default NameOfFunction
```

### 6. What direction are props passed in a React Component?

```sh
Its only in a parent to child direction
```

### 7. How is a React Component accessed in another file?

```sh
You would have to import your react component to your other file for example 
import Movies from './components/Movies'
```

### 8. How do we gain access to props in a child component?

```sh
first thing is to pass props to your function as a parameter 
than you could use {this.props.NameOfTheProp}
```
