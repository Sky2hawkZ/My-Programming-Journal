# React Native - Notes

## Building an App and Deploying it

Build app: react-native init _ProjectName_ (--version X.XX.X)

run app: react-native run-android

## The Rules of state

- Definition of state: a plain javascript object used to record and respond to user-triggered events.
- When we need to update what a component shows, call `this.setState()`
- Only change state with `setState`, do not do `this.state`
- Only use **State** with **class** based components.
- Functional components do no have access to **State**

Speaking of state we use state inside of the album was a component state is a feature of react available
only to class based components state is used to record and react to user interaction.
So in our case we fetch a list of albums and then we assigned or updated our state using the set state
call and or that we only ever update our state object with this data set state.
We never do something like this dot state equals one because we call set state our component instantly
rendered and show the list of albums that it had retrieved after we made our age TTP request.
Next we created an album detail component by mapping over our list of items.