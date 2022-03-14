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
npx create-react-app <app-name>
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
/src/components
```

### 5. What is the syntax for a function based component?

```sh
# In your component.js file...

# Start with importing the react library: 

import React from 'react'

# function syntax here

function ComponentName () {
  const method1 = () => {}

  return (
    <div>
      "content"
    </div>
  );
};

# don't forget to export

export default ComponentName;

```

### 6. What direction are props passed in a React Component?

```sh
Downward
```

### 7. How is a React Component accessed in another file?

```sh
In order to use a React Component in another file you have to import it and add it to the current markup. For example, we did this with <Button /> in the component lesson.
```

### 8. How do we gain access to props in a child component?

```sh
In order to gain access to props in a child component, the props would have to be passed down the component tree. Make sure (props) is an argument and import into the child.

```
