# ReadingsRedux-Advance

### Redux Toolkit

Redux Toolkit was introduced with a purpose to be the standard way to write redux logic. It is said to be an opinionated, batteries-included toolset for efficient Redux development. By using this, you can write all the code you need for your Redux store in a single file, including actions and reducers. Using this you can make your code more readable. Redux toolkit includes all the tools, you want for a Redux application. At the end of the day all you have is less code and faster setups of Redux in every scenario.

Redux Toolkit makes it easier to write good Redux applications and speeds up development, by baking in our recommended best practices, providing good default behaviors, catching mistakes, and allowing you to write simpler code. Redux Toolkit is beneficial to all Redux users regardless of skill level or experience. It can be added at the start of a new project, or used as part of an incremental migration in an existing project.

Note that you are not required to use Redux Toolkit to use Redux. There are many existing applications that use other Redux wrapper libraries, or write all Redux logic "by hand", and if you still prefer to use a different approach, go ahead!

However, we strongly recommend using Redux Toolkit for all Redux apps.

Overall, whether you're a brand new Redux user setting up your first project, or an experienced user who wants to simplify an existing application, using Redux Toolkit will make your code better and more maintainable.



### Creating slice from the redux toolkit

createSlice is a higher order function that accepts an initial state, an object full of reducer functions and a slice name. It automatically generates action creators and action types that correspond to the reducers and state.

In Redux-Toolkit, the createSlice method helps us create a slice of the redux-store. This function aims to reduce the boilerplate required to add data to redux in the canonical way. Internally, it uses createAction and createReducer.

- Step 1: Implement createSilce method and export actions and reducer.
- Step 2: Dispatch action by making use of react hooks in functional component.
- Step 3: Configure the store



You can find more hints & tips from their offical website https://redux.js.org/
