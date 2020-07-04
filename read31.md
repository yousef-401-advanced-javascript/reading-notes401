# Hooks API

## Hooks
React hooks allow to to easily create and manage state in a functional component.

#### Hooks are JavaScript functions, but they impose additional rules:

- Hooks must be named with a use prefix (i.e. useFishingPole)
- Only call Hooks at the top level. Don’t call Hooks inside loops, conditions, or nested functions.
- Only call Hooks from React function components. Don’t call Hooks from regular JavaScript functions. (There is just one other valid place to call Hooks — your own custom Hooks. We’ll learn about them in a moment.)

#### Basic Hooks

- useState
- useEffect
- useContext

#### Additional Hooks

- useReducer
- useCallback
- useMemo
- useRef
- useImperativeHandle
- useLayoutEffect
- useDebugValue