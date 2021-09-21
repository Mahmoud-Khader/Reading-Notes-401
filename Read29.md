# Advanced State with Reducers

![img](https://camo.githubusercontent.com/39edc655449f6262a9a7be81b38da2a83896b55c8c1b146a8922ae1804ccbe91/68747470733a2f2f7265732e636c6f7564696e6172792e636f6d2f64676576653764616f2f696d6167652f75706c6f61642f76313538303636353932322f5573655f526564756365725f536964655f4566666563745f44656d6f2e706e67)

### Review, Research, and Discussion

**1. How can we ensure that an effect hook runs only once?**

* *If we pass an empty array [] , it just renders the component only once like componentDidMount .*

**2. Can useState() update more than one state variable at the same time?**

* *You could combine the state into one state object and then you could do one setState call and there will only be one render. Unlike the setState in class components, the setState returned from useState doesn't merge objects with existing state, it replaces the object entirely.*

```
  const [form, setState] = useState({
    username: '',
    password: ''
  });

```

**3. Is useState() synchronous?**

* *useState and setState both are asynchronous. Even though they are asynchronous, the useState and setState functions do not return promises.*
*Therefore we cannot attach a then handler to it or use async/await to get the updated state values.*

![img](https://i.stack.imgur.com/fNYXc.png)

### Document the following Vocabulary Terms

**1. State Hook**

* *The useState() is a Hook that allows you to have state variables in functional components , it takes the initial state as an argument and returns an array of two entries.*

**2. Component Lifecycle**

* *the series of methods that are invoked in different stages of the component’s existence. The three phases are: Mounting, Updating, and Unmounting.*
