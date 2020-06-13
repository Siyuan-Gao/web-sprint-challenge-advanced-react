Explain how to build stateful class components.
1. Define class and extend react component.
2. Set up constructor then initialize the state.
3. Render UI and return JSX.


Describe the different phases of the component lifecycle.
1. Birth/Mounting Phase - component is being built.
2. Growth/Updating Phase - component data is updating.
3. Death/Unmounting Phase - component is removed.


Demonstrate an understanding of class component lifecycle methods.
1,the constructor function is the first function that gets called Inside of a component. We can use it for data loading requests.
2,componentDidMount gets called exactly one time when our content first shows up on the screen.
3, the render method is the one function that we have to define. This render will get called anytime we decide to update our component.

Define stateful logic.
Stateful logic is any code that uses state.

Describe how to test a React component with React Testing Library.
First you need to import all the dependecies and methods.
1,Arrange: setting up the code that you you needed for testing.
2,Act: calling a method or function that returns a result of interest to our test.
3,Assert: to see if our expected return matched the actual return
