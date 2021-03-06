# Class-29
## Application State with Redux

### Links
- [Dan Abramov Redux Tutorials](https://egghead.io/courses/getting-started-with-redux) (video)
- [Understanding Redux: A Guide](https://www.freecodecamp.org/news/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6/)
- [Testing a React-Redux App using Jest and Enzyme](https://medium.com/netscape/testing-a-react-redux-app-using-jest-and-enzyme-b349324803a9)
- [Testing Redux Reducers with Jest](https://medium.com/@netxm/testing-redux-reducers-with-jest-6653abbfe3e1)
- [Redux Docs](https://redux.js.org/)
- [enzyme-redux npm module](https://www.npmjs.com/package/enzyme-redux)
- [Middleware Tests with a Mock Store](https://gist.github.com/johncokos/4902683c8e33ed38fb2ba066b8764831)



### Discussion Questions
1. **Why would you wrap your entire application within a context?** So that all of the components are descendants and can access state values and setters
2. **What is the purpose of a reducer?** A reducer function determines how to update the state.
3. **What does an action contain?** It contains types that triggers a reducer to be called.
4. **Why do we need to copy the state in a reducer?** Because you can't change the state parameter directly.


#### [Back to Home](README.md)