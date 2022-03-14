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
enter into the file in the terminal and then 
npm start
```

### 4. What folder in a React App should component files be created in?

```sh
src file 
```

### 5. What is the syntax for a function based component?

```sh
function Name() {
logic/variables

return <div></div>
}
export default Name
```

### 6. What direction are props passed in a React Component?

```sh
uni-directional flow
```

### 7. How is a React Component accessed in another file?

```sh
at the end of your component make sure export.
export default ComponentName 

then on your new file import it 
import ComponentName from './components/ComponentName' 

```

### 8. How do we gain access to props in a child component?

```sh
You must set the parameter of your component function to props
function ComponentName(props) {}

now you can call the prop from the app.js in your component function. at the return tag enter in {props.name}
ex. 
function ComponentName (props) {

return <div>{props.name}</div>
}

```
