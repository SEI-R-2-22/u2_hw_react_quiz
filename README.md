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
npx create-react-app my-app
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
import React from 'react'

const RandomExampleFunction = () => {
  return (
    <div>
      <Element />
    </div>
}

export default RandomExampleFunction
```

### 6. What direction are props passed in a React Component?

```sh
They are passed down the tree, so from the parent to the child
```

### 7. How is a React Component accessed in another file?

```sh
You must import the component you want to use at the top of the file
```

### 8. How do we gain access to props in a child component?

```sh
You can access the props in a child component by passing it through the function as an argument and using {} around the prop value inside the function. You use dot notation with the props argument to access the specific value that you want to use.
```
