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
Type into the terminal "create-react-app"
```

### 2. If you clone a React App that has already been created, what command is needed to start developing with its dependencies?

```sh
npm install or npm i
```

### 3. How do you start the in-browser development server for a React App?

```sh
npm start
```

### 4. What folder in a React App should component files be created in?

```sh
src
```

### 5. What is the syntax for a function based component?

```sh
const Button = () => {
  const method1 = () => {}
  const method2 = () => {}
  return (
    <div></div>
  )
}
export default Button
```

### 6. What direction are props passed in a React Component?

```sh
Data Down ---> from App.js towards components (e.g. Button.js, Home.js)
```

### 7. How is a React Component accessed in another file?

```sh
Using Import syntax in the other file:
import Button from '/Button'
```

### 8. How do we gain access to props in a child component?

```sh
Add props to the the component as an arugment:
cosnt Button = (props) => {}
```
