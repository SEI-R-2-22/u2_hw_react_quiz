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
Navigate to the directory for the App, enter the command: "npx create-react-app [name-of-app]"
```

### 2. If you clone a React App that has already been created, what command is needed to start developing with its dependencies?

```sh
Clone repo, use command "npm install" ? 
```

### 3. How do you start the in-browser development server for a React App?

```sh
From within main (master) directory, run command "npm start", then open a new Command terminal if you want to do anything else, since the first one is now running your live server :) 
```

### 4. What folder in a React App should component files be created in?

```sh
In the "src" directory
```

### 5. What is the syntax for a function based component?

```sh
import React from 'react'

function ComponentName(props) {
  ...
  return (
    <div>
      DOM-style html content, with only one parent-level element, and everything else contained within
    </div>
  )
}

export default ComponentName
```

### 6. What direction are props passed in a React Component?

```sh
Unidirectionally, from Parent Component → Child Component
```

### 7. How is a React Component accessed in another file?

```sh
At the top of the .js file, use: 
"import ComponentName from './ComponentName'
```

### 8. How do we gain access to props in a child component?

```sh
First, you have to pass props from the Parent component via the HTML tags, e.g.:

"<ComponentName text="string content here" myFunction={someFunctionName / Array / Object / Etc.}>"

...and then in the child component, call "props" as the function argument, and then use {dot.notation} to access, e.g:

"ComponentName(props) {
  return (
    <div>
      <button onClick={props.myFunction}>
        {props.text}
      </button>
    </div>
  )
}"
```
