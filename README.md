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
Your answer here
```

### 2. If you clone a React App that has already been created, what command is needed to start developing with its dependencies?
```sh
Your answer here
```

### 3. How do you start the in-browser development server for a React App?
```sh
Your answer here
```

### 4. What folder in a React App should component files be created in?
```sh
Your answer here
```

### 5. What type of component do you need to be able to use state?
```sh
Your answer here
```
### 6. In what order are these methods called in a React Class Component? (`render`, `componentDidMount`,`constructor`)
```sh
Your answer here
```

### 7. What direction are props and state passed in a React Component?
```sh
Your answer here
```

### 8. How is a React Component accessed in another file?
```sh
Your answer here
```

### 9. In what lifecycle method do we typically make API calls?
```sh
Your answer here
```

### 10. Why is `this.state` declared in a constructor?
```sh
Your answer here
```

### Bonus: In looking at this code, why will our todos not be displayed on the page? Find the bug and fix it.
```js
/* App.js */
class App extends React.Component {
  constructor() {
    super()
    this.state = {
      todos: []
    }
    console.log('Constructor')
  }
  componentDidMount() {
    console.log('Mounted')
    // Pretend Api Call
    this.setState((prevState) => ({
      todos: todos
    }))
  }
  render() {
    console.log('Rendering')
    return (
      <div className="App">
        <Wrapper />
      </div>
    )
  }
}

export default App
/* App.js */


/* Wrapper.js */
import Content from './Content'
import Footer from './Footer'
import Header from './Header'

const Wrapper = (props) => {
  // console.log(props)
  return (
    <main>
      <Header />
      <Content todos={props.todos} />
      <Footer />
    </main>
  )
}

export default Wrapper
/* Wrapper.js */


/* Content.js */
const Content = (props) => (
  <section>
    {props.todos.map((todo, index) => (
      <TodoItem key={index} todo={todo} />
    ))}
    {/* 
    Nothing will be rendered on the screen.
     */}
  </section>
)

export default Content
/* Content.js */


/* TodoItem.js */
const TodoItem = (props) => {
  const { date, todoText, completed } = props.todo
  return (
    <div>
      <p>Date: {date}</p>
      <p>My Todo: {todoText}</p>
      <p>Completed: {completed}</p>
    </div>
  )
}

export default TodoItem
/* TodoItem.js */

```

