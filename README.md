# generic-context

withContext(component) -> injects context as props in the provided component;
generateContext(actions, ...contexts) -> merges actions and multiple contexts into one context state;
createAction(request, functionalSetState) -> creates an object with an API request and a final functionalSetState to update context;
