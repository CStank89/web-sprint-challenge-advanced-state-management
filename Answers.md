1.  What problem does the context API help solve?
    The Context Apit helps solve the specific problem in react of sharing state down a component tree. This ensures we dont have to 'prop drill'

1.  In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
    Store: is where our state is held
    Actions: are parloads of information that send date from our app to the store. They are the only source of imformation from the store
    Reducers: are functions that specify how the apps state changes in response to the actions sent.

1.  What is the difference between Application state and Component state? When would be a good time to use one over the other?
    Component state is generally sotred locally within the compoent and is not accessible form other components unless passing props. Application state is globally accessed state.

1.  Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?
    Redux-Thunk is a middleware that allows us to write action creators that return a function instaed of an action.
1.  What is your favorite state management system you've learned and this sprint? Please explain why!

        Context API.  It makes sense for the scale of things we have been taught and worked on.  None of these projects really REQUIRE redux imo.  Redux definetly is needed and has its place.  Redux Hooks I think will be a game changer once I learn more about them.
