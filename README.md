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
We can use create-react-app to create a React App. We call it using the command npx create-react-app my-app. This will then generate a folder called my-app. In there, we can find the src folder where we can write the majority of our code.
```

### 2. If you clone a React App that has already been created, what command is needed to start developing with its dependencies?

```sh
npm install
```

### 3. How do you start the in-browser development server for a React App?

```sh
npm start command in the terminal
```

### 4. What folder in a React App should component files be created in?

```sh
src folder
```

### 5. What is the syntax for a function based component?

```sh
Its name should be written in Pascal Case (but that is a convention). Its return statement includes the HTML-appearing elements that will be displayed. After the completion of the function, an export statement needs to be used for the component to be accessed by other places.
```

### 6. What direction are props passed in a React Component?

```sh
Props are passed downward. It is best practice to keep them as high in the tree as possible so that they can be correctly used by any components further downstream.
```

### 7. How is a React Component accessed in another file?

```sh
The other file needs to have an import statement. The React Component is imported from its location in the file directory using './' at the start of its file path.
```

### 8. How do we gain access to props in a child component?

```sh
We use syntax similar to string literals where the prop names are written inside curly braces.
```
