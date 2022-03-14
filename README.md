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
First, navigate to your project directory. Run the command % npx create-react-app my-app
```

### 2. If you clone a React App that has already been created, what command is needed to start developing with its dependencies?

```sh
After forking and cloning, within the appropriate directory run the command % npm install
```

### 3. How do you start the in-browser development server for a React App?

```sh
Within the appropriate directory, run the command % npm start
```

### 4. What folder in a React App should component files be created in?

```sh
Component files should be created within the src/components/ directory.
```

### 5. What is the syntax for a function based component?

```sh
function ComponentName() {
  // Component method(s), if any go here.
  return (
    <div>
    // UI Element(s) go here.
  </div>
  )
}

export default ComponentName

Component name is written in PascalCase.
```

### 6. What direction are props passed in a React Component?

```sh
props are always passed in a downward direction (from parent to child).
```

### 7. How is a React Component accessed in another file?

```sh
React Components can be accessed from other files using import and export statements.

At the end of a component file, the component should be exported so that it can be used in other locations within the application:

// Inside component file:

export default ComponentName

Then, in the beginning of the App.js file, an import statement should be added at the TOP of the file to access the exported component:

//Inside App.js file:

import ComponentName from './components/ComponentName'

```

### 8. How do we gain access to props in a child component?

```sh
props are objects that are defined in the App.js page and  written with JSX syntax that looks similar to html elements:


// within App.js file:

example: <ComponentName propName="Prop Value /">
example (with variable): <ComponentName propName={propVariable}>

We gain access to props by passing them through the child component function in the following fashion:

// within './components/ChildComponent' file:

function ChildComponent(props) {
  return <element>{props.propName}</element>
}

the propName is appended to the props object that is passed into the function. This all takes place within curly brackets, as props are essentially variables within React.
```
