# Answers

1. What is React JS? How does it differ from other JavaScript frameworks?

React is a Javascript framework that emphasises on component based design and state management. A big part of React is it's controlled data flow in which the state that is usualy held by the parent element also controls what is rendered to the screen.


2. Explain briefly the React Component Lifecycle. Name three of the methods that are a part of the lifecycle and what they do.

The React Component lifecycle is essentially what happens to a component as it is altered, refreshed and then put back into a resting state of sorts. Thre of the most common lifecycle methods are componenetWillMount, componentDidMount(although this is being depreciated) and componentWillUnmount.


3. Briefly describe some of the differences between a Class/Stateful component and a Functional/Presentational component.

Class componenets extend the React Component class and are best suited to carry state within them. Functional componenets are primarily used to render a componenet to the screen while having state(or the effects of state) trickle down to it through props.


4. Briefly describe PropTypes and what we use them for when building react applications.

PropTypes are mainly used for developmental purposes. They ensure that the data types being input are those that are expected. You can also set required props. All of this helps when reusing componenets, ensuring that they are used properly.