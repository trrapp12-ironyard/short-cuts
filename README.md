# short-cuts

| Things I do in VS Code                 | Shortcut                                 | 
| :--------------------------------------| ----------------------------------------:| 
| open VS Code                           |                                          | 
| Opens the palette to search for a file |   Mac: CMD + P <br> Windows/Linux: CTRL + P   |
| Add cursor to matching selections.     |   Mac: CMD + SHIFT + L                    |
Windows/Linux: CTRL + SHIFT + L





1. 

Import/export errors: Make sure the component is properly imported and exported. Check for typos in file names, paths, and named exports.

Component not used: Ensure that the component is actually being used in the parent component or app.

Render method issues: Verify that the component has a valid render method or is using the correct syntax for functional components.

Conditional rendering: Check if the component is conditionally rendered and the condition is not being met.

Incorrect prop values: Ensure that the component is receiving the correct props and that any required props are being passed down.

State issues: Check if the component's state is being initialized and updated correctly. Look for issues with setState or useState hooks.

Lifecycle methods: If using class components, verify that the lifecycle methods are being used correctly and not preventing the component from rendering.

React key prop: If the component is part of a list, make sure you're using the 'key' prop with unique values.

CSS and styling: Inspect your CSS and styling to ensure the component is not being hidden or visually obstructed.

Higher-order components (HOCs) and wrappers: If your component is wrapped by an HOC, ensure that the HOC is passing down the necessary props and rendering the component correctly.

JavaScript errors: Check the browser console for any JavaScript errors that may prevent the component from rendering.

Version mismatches: Make sure your React and ReactDOM versions are compatible.

Third-party libraries: Ensure that any third-party libraries being used are compatible with your React version and properly configured.
