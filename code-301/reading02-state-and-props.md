# State and Props

### [React Lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)
#### 1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
- render

#### 2. What is the very first thing to happen in the lifecycle of React?
- Mounting

#### 3. Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`
- 'constructor' , 'render' , 'componentDidMount' , 'React Updates' , 'componentWillUnmount'.

#### 4. What does 'componentDidMount' do?
- This method is invoked immediately after a component is mounted. If a developer needs to load anything using a network request or initialize the DOM, it should be put here. 
- This method is a good place to set pu any subscriptions. If that is the case, do not forget to unsubscribe in 'componentWillUnmount()'

### Video: [React lifecycle](https://www.youtube.com/watch?v=IYvD9oBCuJI)
#### 1. What types of things can you pass in the props?
- Per [ChatGPT.com](https://chat.openai.com/share/5f5b55a3-9508-4c78-812a-420c2cf46965), props can be used to pass various types of data including, but not limited to:
  - Primitive data types:
    - Strings
    - Numbers
    - Booleans
  - Functions:
    - Callback functions can be passed as props to child components, allowing communication between components and enabling child components to trigger actions in parent components.
  - Objects and Arrays:
    - Objects and arrays can be passed as props. These can hold more complex data structures and are useful for passing multiple values as a single prop.

#### 2. What is the big difference between props and state?
- Props can be thought of as arguments to a function. They are used for passing data from parent to child commponents and are immutable (unchangeable).
- Props are for things that you pass, like a function. They are what you want to initialize your component to OR what you want your component to render like.
- Used when a developer wants to display some information inside of a componenet without hard coding it. It is essentially a variable to a function.

- State is something *inside* of a component.
- The biggest differences between **props** and **state**:
  - Props are passed into a component.
  - State is then handled *inside* of that component and props are handled *outside* of the component.
- In summary: state is handled in the component and it can be updated inside the component while props are handled outside the component and must be updated outside of the component.

#### 3. When do we re-render our application?
- Whenever the state is changed inside of the applicaton.
- State is there for when a developer needs to actually rerender and update the application based on something the user has done (ie. clicking on an image and updating the number of clicks - odd-duck)
- If something in the application needs to have the ability to change, it should be stored in state so that it will properly rerender when it changes.

#### 4. What are some examples of things that we could store in state?
- State would be useful inside of a form (checkbox, select a box, anything requiring some user input).
- These examples need to have the ability to be updated by the user, so the developer would use state to store what the user is updating/changing that value to.


## Keep in Mind
- Often times, new developers get confused when deciding to use state vs props.
- Make sure to think about which one is going to be handled by the component.
  - If that piece of information is being handled inside the component and inside that component **only** (nowhere outside of it like a parent, for example), then use state.
  - If that information is being handled outside the component (in a parent, for example), then it needs to be passed in via props.
- If the information is static and not going to change (example: a dev would never need to update the title of a display section), then you would want to use props because props are for things that are going to be passed down from the parent and do not change inside the component.


## Things I Want to Know More About
- React Docs - [State and Lifecycle](https://legacy.reactjs.org/docs/state-and-lifecycle.html)
- React Docs - [handling events](https://legacy.reactjs.org/docs/handling-events.html)
- React Tutorial through [‘Developer Tools’](https://react.dev/learn/tutorial-tic-tac-toe)
- React [Bootstrap Documentation](https://react-bootstrap.github.io/)
- Boootstrap [Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)
- [Bootstrap Shuffle - a class “sandbox”](https://bootstrapshuffle.com/classes)
- [Netlify](https://www.netlify.com/)