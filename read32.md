# Custom Hooks
Custom Hooks are a mechanism to reuse stateful logic (such as setting up a subscription and remembering the current value), but every time you use a custom Hook, all state and effects inside of it are fully isolated

### What are custom hooks?
- Extract duplicated logic from components
- Share common functionality
- Take advantage of useEffect lifecycle

### Common use cases
- make things DRY!
- Handle forms easily
- Pre-fetch API data
- Connect to services (like socket.io, Q, etc)

### useReducer 
is one of a handful of React hooks that shipped in React 16.7.0. It accepts a reducer function with the application initial state, returns the current application state, then dispatches a function.