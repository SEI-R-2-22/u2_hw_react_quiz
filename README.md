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
npm create-react-app name_of_app
```

### 2. If you clone a React App that has already been created, what command is needed to start developing with its dependencies?

```sh
npm install
```

### 3. How do you start the in-browser development server for a React App?

```sh
In the terminal type: npm start
```

### 4. What folder in a React App should component files be created in?

```sh
In the src folder
```

### 5. What is the syntax for a function based component?

```sh
function ComponentName () {
  const method = () => {}

  return <div> </div>
}

export default ComponentName
```

### 6. What direction are props passed in a React Component?

```sh
Props are pieces of information passed in a uni-directional flow (one way from parent to child).
```

### 7. How is a React Component accessed in another file?

```sh
In order to access a component in another file, you have to import the component at the top of the .js file you are working on. Once it is imported you can go ahead and call the component into your file. Example of the syntax is below.

import ComponentName from "./components/ComponentName"

<div>
  <ComponentName />
</div>
```

### 8. How do we gain access to props in a child component?

```sh
Props needs to be passed as a parameter when creating the component function. Since props is an oject that contains properties as a key/value pair. Use {} to access the prop and the name of the key to get the value.
ex: <Button {props.text}
```
