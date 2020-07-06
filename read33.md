# Context API

### Context
Context provides a means of passing state down the component tree through a Provider/Consumer relationship.<br />  
At as high a level as makes sense, a “provider” can make it’s state available, along with means of altering it (methods).<br />  
At the lower levels any component can “opt-in” and become a “consumer” and receive this.state from context.<br />  

**Context** is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language
