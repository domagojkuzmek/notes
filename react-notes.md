- JSX is a syntax extension for JavaScript that allows you to describe your UI in a familiar HTML-like syntax
- User interfaces can be broken down into smaller building blocks called components
- PROPS, or custom arguments, change the component's behavior or what is visibly shown when it's rendered to the screen, props are read-only informationgi
- since props is an object, you can use object destructuring
- HOOKS, set of functions, hooks allow you to add additional logic
- state as any information in your UI that changes over time
- you can pass the state information to children components as props, but the logic for updating the state should be kept within the component where state was initially created


-package-lock.json file that contains detailed information about the exact versions of each package
- With dynamic rendering, your application is only as fast as your slowest data fetch.