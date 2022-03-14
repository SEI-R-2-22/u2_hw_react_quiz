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
run npm start in the app directory
```

### 4. What folder in a React App should component files be created in?

```sh
component directory in src folder
```

### 5. What is the syntax for a function based component?

```sh
-pascal case
-function defines component
-method called useState is used
-return React.createElement()
-append to dom with ReactDOM.render
```

### 6. What direction are props passed in a React Component?

```sh
down
```

### 7. How is a React Component accessed in another file?

```sh
after being exported from its own file, it is imported at the top of the desired file like so

import MyComponent from './componentpath'
```

### 8. How do we gain access to props in a child component?

```sh
the keyword props is passed as an argument in the child component file, then the props keyword is placed in curly brackets (with dot notation variables) where we want our data to go. In the parent component, we can pass data into the child component almost like HTML attributes using those designated variables. (hope this makes sense)
```
