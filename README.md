# React intro

## Introduction to course
- Goals:
    - The students will know...
    1. how to easily set up a new React app with create-react-app
    1. what a WebComponent is, how to make and use them in React.
    1. What advantages WebComponents provide.
    1. what *state* in a component is.
    1. how to watch for changes in values with `useEffect`. 
    1. how a parent component can communicate with a child component via *props*.
    1. how a child component can communicate with a parent component via *callbacks* in props.
    1. how to set up a form in React.  
    1. what Redux is, and what problem it solves.
- Will be hands-on if you want to.
    - Code along or just watch.
    - Will use repl.it. 

## Introduction to React
- Created by Facebook
- Regularly among the top three frameworks.
- WebComponents
    - Can be reused & encapsulated.
    - Are shorter.
    - Easier to change 
- Interactivity is easier.
    - Automatically listen to changes in variables etc. and respond.
 
 ## Set up everything
 `npx create-react-app geo-weather`
 
 - What is `NPX` and what is `create-react-app`?
    - Difference between `npm` and `npx`?
- Go to repl.it
- Explain how repl.it works
    - Live coding
    - Can see what the other people are selecting. 

## Introduce components, states, and props
- Make a simple component. Duplicate it and send props to it.
- Make another simple component. Use this component both in component 1 and in the parent component.
- Turn the simple component into a counter. Use state.
    - Explain what Redux is

## Introduce the app
- A little app where a user can enter latitude and longitude, and see the temperature in that place.
- We will have two components
    - LocationForm
    - TemperatureDisplay
- Make dummy components.

## Toolbar
- Make two inputs and a button.
- Show how you use the form.
    - Mention Formik.
- Show how the position can be sent to the parent component through a callback.
- Make state in parent component.

## TemperatureDisplay
- Show how we can use useEffect to subscribe to changes in props.
    - Otherwise we would have to fetch from API each time a component is rerendered.
    - Show useEffect with empty array as argument.
- Either generate a random temperature or actually fetch it from https://api.met.no/weatherapi/locationforecast/2.0/compact?lat=60.10&lon=9.58
- Show React component navigator in Chrome.

## Conclusion. Show goals and go through them again.
