# Redux Counter App
This is a simple React application that demonstrates the use of Redux with the Redux Toolkit. It includes a counter that can be incremented, decremented, and toggled on and off. The project showcases two different implementations of the same functionality: one using functional components and hooks, and the other using class components and the traditional way of connecting Redux.

# Functional vs. Class-based Components
The project provides both functional and class-based components for the counter. You can choose which one to use based on your preference. The functional component (Counter.js) uses React hooks and React-Redux's useSelector and useDispatch to manage state and dispatch actions, while the class-based component uses the older connect method with mapStateToProps and mapDispatchToProps.

# Redux Setup
The Redux setup is done using the @reduxjs/toolkit. It creates a Redux store with two slices: one for the counter state and one for authentication. You can extend this setup to manage more complex application states.

# Features
Increment the counter by 1.
Decrement the counter by 1.
Increase the counter by a specified amount (5 in this case).
Toggle the counter's visibility on and off.

# Project Structure

Functional Component Implementation:
The functional component implementation can be found in the Counter.js file.
It uses React hooks like useSelector and useDispatch to interact with Redux.
Redux state management is done using @reduxjs/toolkit, including the creation of a Redux store and slices for counter and authentication.

# Redux Setup:

The Redux store is configured using configureStore from @reduxjs/toolkit.
Separate slices are created for the counter and authentication states using createSlice.

# Technologies Used
- React
- Redux
- Redux Toolkit
- CSS Modules

<img width="1920" alt="Screen Shot 2023-10-12 at 9 08 35 PM" src="https://github.com/EmirPirija/redux-counter-with-auth/assets/118456820/84af04b8-ef50-42c0-ad17-b95542a9031e">
<img width="1920" alt="Screen Shot 2023-10-12 at 9 08 53 PM" src="https://github.com/EmirPirija/redux-counter-with-auth/assets/118456820/35d59634-477e-47f4-ae00-922715436ef3">
