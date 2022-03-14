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
Run the terminal command: npx create-react-app my-app.
```

### 2. If you clone a React App that has already been created, what command is needed to start developing with its dependencies?

```sh
Run the terminal command: npm install.
```

### 3. How do you start the in-browser development server for a React App?

```sh
Run the terminal command: npm start.
```

### 4. What folder in a React App should component files be created in?

```sh
A folder titled components within the src folder.
```

### 5. What is the syntax for a function based component?

```sh
function Button (props) {
  return <button> {props.title} </button>
}
```

### 6. What direction are props passed in a React Component?

```sh
Props are passed downward within a React Component.
```

### 7. How is a React Component accessed in another file?

```sh
First you export it from the file it exists in using the name of the React Component. Then you import it into the chosen file using the React Component name and the relative path to the React Component file.
```

### 8. How do we gain access to props in a child component?

```sh
You pass the word props into the parameter for the function based component. Then you use brackets and dot notation to access the specific component. Example: {props.title}.
```
