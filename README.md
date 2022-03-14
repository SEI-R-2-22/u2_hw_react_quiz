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
create-react-app
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
components
```

### 5. What is the syntax for a function based component?

```sh
function Shows(props) {
  return <button onClick={props.handleClick}>{props.text}</button>
}
```

### 6. What direction are props passed in a React Component?

```sh
passed down
```

### 7. How is a React Component accessed in another file?

```sh
by using import at the top of the page.
import Shows from './components/Movie'
```

### 8. How do we gain access to props in a child component?

you insert props into the function
return what you need
use dot notation to use they key to call what you need. ex. {props.poster}, {props.shows}, {props.episodes}

```sh
Your answer here
```
