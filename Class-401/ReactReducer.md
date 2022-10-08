# React Reducer

## How can we ensure that an effect hook runs only once?
pass an empty array ([]) as a second argument. This tells React that your effect doesn’t depend on any values from props or state, so it never needs to re-run. 

## Can useState() update more than one state variable at the same time?
no useState can only update one state variable at a time.

## Is useState() synchronous?
useState is an asynchronous hook

## State Hook: The useState() is a Hook that allows you to have state variables in functional components.
so basically useState is the ability to encapsulate local state in a functional component.

## Component Lifecycle: series of methods that are invoked in different stages of the component’s existence
