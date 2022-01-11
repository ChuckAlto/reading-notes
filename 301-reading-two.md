# 301 Reading Two

## React Lifecycle

- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

Answer- The render

- What is the very first thing to happen in the lifecycle of React?

Answer- it appears that mounting the constructor comes first.

- Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

Answer- constructor, render, componentDidMount, React Updates, componentWillUnmount.

- What does the componentDidMount do?

Answer- invoked after a component is mounted, loads anything using a network request, good for setting up subscriptions.

## React State Vs Props

- What types of things can you pass in the props?

answer- initial count, titles, subtitles,

- What is the big difference between props and state?

Answer- props pass into a component state is handled inside the component, props are handled outside the component.

- When do we re-render our application?

Answer- when state is changed inside the application, props must be changed outside the component.

- What are some examples of things that we could store in state?

Answer- anything that needs to change within an application, such as a counter.

[Main](README.md)
