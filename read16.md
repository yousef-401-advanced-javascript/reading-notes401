# Event Driven Applications

**Event-Driven Programming :** is a logical pattern that we can choose to confine our programming within to avoid issues of complexity and collision<br />

#### Event-Driven Programming makes use of the following concepts:

- An Event Handler is a callback function that will be called when an event is triggered.
- A Main Loop listens for event triggers and calls the associated event handler for that event.

### Event Emitter
its used to get started incorporating Event-Driven Programming in the project right away.<br />

### Removing Listeners
when you want to remove an event listener from an event. This could be for performance reasons (the event is no longer needed) or to avoid memory leaks (if an event listener references an object that is no longer needed, it won’t be able to be garbage-collected. This can lead to a build up of unnecessary objects).

