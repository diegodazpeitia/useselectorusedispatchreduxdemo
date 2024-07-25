# React-Redux Counter Example

This project demonstrates how to use Redux with React to manage global state. It leverages the `react-redux` library to integrate Redux into a React application, utilizing the `useDispatch` and `useSelector` hooks.

## Core Concepts

### Redux

**Redux** is a state management library for JavaScript applications. It provides a predictable way to manage and update application state. Key concepts include:

- **Store:** A single, centralized place to store the entire state of the application. It allows you to access and modify the state in a consistent way.
- **Actions:** Plain objects that represent events or intentions to change the state. Actions typically include a `type` field and can carry additional data.
- **Reducers:** Functions that specify how the state changes in response to actions. Reducers take the current state and an action as arguments and return a new state.
- **Dispatch:** A method used to send actions to the Redux store to trigger state changes.

### React-Redux

**React-Redux** is a library that provides bindings to integrate Redux with React. It simplifies the process of connecting React components to the Redux store. Key concepts include:

- **Provider:** A component that makes the Redux store available to any nested components that need access to it. It wraps the root of the application.
- **useSelector:** A React-Redux hook that allows you to read data from the Redux store. It lets you select a piece of state from the store and subscribe to updates.
- **useDispatch:** A React-Redux hook that provides a reference to the `dispatch` function from the Redux store. It allows you to send actions to the store to update the state.

## Setup and Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/diegodazpeitia/useselectorusedispatchreduxdemo.git
   cd useselectorusedispatchreduxdemo
   ```

2. **Install Dependencies**

   Ensure Node.js and npm or yarn are installed, then install the project dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run the Application**

   Start the development server:

   ```bash
   npm start
   # or
   yarn start
   ```

   Navigate to `http://localhost:3000` in your browser to view the application.

## Usage

This application demonstrates a simple counter that uses Redux to manage its state. The counter value is displayed and can be incremented using a button. The `useSelector` hook is used to access the counter value from the Redux store, and the `useDispatch` hook is used to dispatch actions that update the counter.

## Key Benefits

- **Predictable State Management:** Redux provides a clear and predictable way to manage application state, making it easier to understand and debug.
- **Component Decoupling:** React-Redux hooks allow components to access state and dispatch actions without tightly coupling them to the Redux store.
- **Centralized State:** With Redux, the application state is centralized in one store, which helps in maintaining consistency and managing state changes in a single place.

# What you will experience 

<img width="510" alt="Captura de pantalla 2024-07-25 a la(s) 13 47 54" src="https://github.com/user-attachments/assets/52949a42-5d98-4a5f-8ac0-00537f4937f0">


## Contributing

Contributions to improve or extend this project are welcome. Please submit issues or pull requests as needed.

## License

This project is licensed under the MIT License.
