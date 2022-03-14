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
In your terminal command line creating a React App would look something like;
"Create_react_app" then in that same command line you will name your app "name_here_app".
```

### 2. If you clone a React App that has already been created, what command is needed to start developing with its dependencies?

```sh
If you cloned a React App you would want to NPM install to start the development of its dependencies.
```

### 3. How do you start the in-browser development server for a React App?

```sh
After an npm install and opening your React app in your choosen code editor, to open the in-browswer development, go to your terminal and in its command line type "Npm start".
```

### 4. What folder in a React App should component files be created in?

```sh
"src" contains dynamics of the React app. Any other folder outside of "src", dependecies would be added to the gitignore.
```

### 5. What is the syntax for a function based component?

```sh
The function based component uses PascalCase.

function ComponentName (){
  const method1 = () => {} ------ logic/variables
  const method2 = () => {}
  
  return <div></div> ----elements to display
}
export default ComponetName ----export statment to use the componet in other places

resource: https://github.com/ayyyecraig/u2_lesson_react_components
```

### 6. What direction are props passed in a React Component?

```sh
Props in a React Componet flow downwards. Parent to child so on so forth.
```

### 7. How is a React Component accessed in another file?

```sh
Using object.notation and import child from 'react'.
```

### 8. How do we gain access to props in a child component?

```sh
Create function inside the parent. Pass the function name as a prop into another child. Then call the fucntion to pass in the data as an argument.
```
