
# What is JSX, and why is it used?

JSX (JavaScript XML) is a syntax extension for JavaScript commonly used in React to define the structure of user interfaces. It allows developers to write HTML-like elements directly within JavaScript, making the UI code more readable and easier to visualize. JSX is later compiled into standard JavaScript function calls (such as React.createElement()).

# What is the difference between State and Props?

In React, Props are external data passed from a parent component to a child component. They are read-only and cannot be modified by the receiving component.
State, on the other hand, represents internal data that is managed and updated within a component. When a component’s state changes, React automatically re-renders the UI to reflect the new data.

# What is the useState hook, and how does it work?

The useState hook is a built-in React function that enables functional components to manage local state. It returns an array with two elements:
The current state value, and
A function to update that value.
When the update function is called, React re-renders the component with the updated state, ensuring the UI stays in sync with the data.

# How can you share state between components in React?

State can be shared between components in several ways depending on the app’s structure and complexity:
Props – To pass state from a parent to a child component.
Lifting state up – Move shared state to the closest common ancestor of sibling components.
Context API – To share data globally without manually passing props through multiple levels (avoiding “prop drilling”).
State management libraries – Use tools like Redux, Zustand, or Recoil for managing complex or global application state.

# How is event handling done in React?

React handles events using its synthetic event system, which ensures consistent behavior across browsers. Event names follow camelCase conventions (e.g., onClick instead of onclick), and event handlers are passed as functions, not strings. For example:
 
button onClick={handleClick}>Click Me button


This approach allows React to efficiently manage events and ensure cross-browser compatibility.# Customer_Support
# Customer_Support
