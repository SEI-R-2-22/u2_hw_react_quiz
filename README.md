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
npx create-react-app "app-name-goes-here"
```

### 2. If you clone a React App that has already been created, what command is needed to start developing with its dependencies?

```sh
npm install
```

### 3. How do you start the in-browser development server for a React App?

```sh
You type in 'npm start' in the terminal
```

### 4. What folder in a React App should component files be created in?

```sh
In the "components" directory in the src folder
```

### 5. What is the syntax for a function based component?

```sh
const Welcome = (props) => { 
  return <h1>Hello, {props.name}</h1>; 
}
```

### 6. What direction are props passed in a React Component?

```sh
From parent to child, and not child to parent
```

### 7. How is a React Component accessed in another file?

```sh
You import the component on the other file at the top.
(Ex. import Movie from "./components/Movie")
```

### 8. How do we gain access to props in a child component?

```sh
You pass the props to the child component and while in the child
component you can access it by writing the variable only
<Component propName={propData} />
```
