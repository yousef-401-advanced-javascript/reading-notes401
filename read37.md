# Combined Reducers
Combined reducers is pulling in more than one reducer from source and creating a keyed object from them.


#### There are several important ideas to be aware of when using combineReducers:
- First and foremost, combineReducers is simply a utility function to simplify the most common use case when writing Redux reducers.
- While Redux itself is not opinionated about how your state is organized, combineReducers enforces several rules to help users avoid common errors.
- You can use it at all levels of your reducer structure, not just to create the root reducer. It's very common to have multiple combined reducers in various places, which are composed together to create the root reducer.

#### the point
Obey the Single Responsibility Principle, each reducer really should have only 1 part of state to manage

### the actions

- Each reducer technically has it’s own actions and creators.
- they can cross over and both be dispatched.
  - This can be` very powerful, as often times actions are valid for multiple reducers
  - this behavior needs to be well understood or it’ll cause unintended consequences.