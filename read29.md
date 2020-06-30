# Component Composition

### Routing
Using react-router, you can easily toggle the visibility of components (or even pages) based on the URL/Route that the user engages with.
When starting a new project, you need to determine which type of router to use. For browser based projects, there are <BrowserRouter> and <HashRouter> components. The <BrowserRouter> should be used when you have a server that will handle dynamic requests (knows how to respond to any possible URI), while the <HashRouter> should be used for static websites (where the server can only respond to requests for files that it knows about).

Usually it is preferable to use a <BrowserRouter>, but if your website will be hosted on a server that only serves static files, then the <HashRouter> is a good solution.

For our project, we will assume that the website will be backed by a dynamic server, so our router component of choice is the <BrowserRouter>.
