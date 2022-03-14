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
npx create-react-app app-name
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
Inside the src/ directory (more specifically, often inside a components/ subdirectory within src/)
```

### 5. What is the syntax for a function based component?

```sh
The name of a functional component is PascalCased. The functional component body includes component-specific variables and logic, and it must include a return statement to display UI elements. Beneath the functional component declaration, we must include an export statement. Here is an example of a functional component:
const MyFunctionalComponent = () => {
  return (
    <div>
      <h1>Some code to display in the UI goes here</h1>
    </div>
  )
}
export default MyFunctionalComponent
```

### 6. What direction are props passed in a React Component?

```sh
Props are passed downward from parent to child components. There is a unidirectional data flow.
```

### 7. How is a React Component accessed in another file?

```sh
The file in which the functional component is declared must include an export statement, and the component is then imported into another file by using an import statement, e.g., import Movie from './Movie'
```

### 8. How do we gain access to props in a child component?

```sh
When a child component is rendered from a parent component, props are passed from the parent component to the child component using the syntax: <ChildComponent propName={propValue} />
Properties are then accessed in the child component by extracting them from the prop object using dot notation.
```
