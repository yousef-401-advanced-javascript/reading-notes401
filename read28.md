# Props and State
### Forms
HTML form elements work a little bit differently from other DOM elements in React, because form elements naturally keep some internal state.

### Props
Components accept arbitrary inputs called props. In JSX, props are passed into a component with a syntax that looks like HTML attributes. These are the equivalent of function params.

In actuality, props is the name of the object passed into a component constructor and any prop added to a component in the JSX will be accessible as a property on props.

After props is passed into the constructors super function, they are available on the context by using this.props.

