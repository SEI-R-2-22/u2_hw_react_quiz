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
npx create-react-app my-app (my-app could be named anything)
```

### 2. If you clone a React App that has already been created, what command is needed to start developing with its dependencies?

```sh
run npm install from your terminal in the directory which contains package
```

### 3. How do you start the in-browser development server for a React App?

```sh
After you are in your my-app diectionary, run npm start
```

### 4. What folder in a React App should component files be created in?

```sh
You can mkdir a new folder in your SRC and call it "components" . All components should be kept in that.
```

### 5. What is the syntax for a function based component?

```sh
-They should always be PascalCased
-We also have to use the import syntax to call upon any function componants 
ex) 
import React from 'react’

function App() {

return <h1>{hello}</h1>;

}

export default App;
```

### 6. What direction are props passed in a React Component?

```sh
Parent -> Child component down the component tree.
```

### 7. How is a React Component accessed in another file?

```sh
It has to be imported and then called within a function in the new folder
```

### 8. How do we gain access to props in a child component?

```sh
We use prop. within the {} syntax only after plugging props into the child function 
```
