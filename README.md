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
After cd-ing to your directory of choice (within the terminal), run the command "npx create-react-app [name]", replacing "[name]" with whatever you wish to call your React App.
```

### 2. If you clone a React App that has already been created, what command is needed to start developing with its dependencies?

```sh
After forking and cloning, run (in terminal) "npm install", then "code .", "npm start".
```

### 3. How do you start the in-browser development server for a React App?

```sh
In the directory for your React App run the command "npm start".
```

### 4. What folder in a React App should component files be created in?

```sh
In a folder named "components".
```

### 5. What is the syntax for a function based component?

```sh
function ComponentName() {
  return <div></div>
}
```

### 6. What direction are props passed in a React Component?

```sh
Downwards.
```

### 7. How is a React Component accessed in another file?

```sh
To access your React Component in another file you have to "import" it with a line of code using the format: " import React from 'react' "
```

### 8. How do we gain access to props in a child component?

```sh
After importing your React Component, you can access whichever prop you are interested in, first by creating a function with "props" in the parameter, and then in the location that you want to place it, by using the syntax " { props.blank } ". "blank" here represents whatever you named your prop in your React Component.
```
