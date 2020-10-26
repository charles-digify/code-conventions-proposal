# Proposal for Code Conventions

## Frontend

### In React code...
- **Use comments and JSDoc as much as possible.**
- Use hooks.
- Use Function Components as much as possible.
- In creating functions inside components, use the arrow function syntax (to avoid confusion with the component's function).
- Avoid using inline styles (`style={}`) in components as much as possible. Put custom styles in the corresponding SCSS files.
- Use named imports and exports as much as possible.
```js
export const myExport = something;

import { myExport } from './myExport';
```
- If there are a lot of props, try to follow the following format:  
```html
<MyComponent
	className="my-component"
	id="my-component-1"
	myProp={someData}
	myProp2={someData2}
	ref={someRef}
	onClick={someClickHandler}
>
	some content
</MyComponent>
```
- Resolve the warnings that are shown in the console as much as possible.
- Use trailing commas for array elements and function parameters that are separated by line.
```js
const array =
[
	'this is a long line of text',
	'this is a long line of text',
	'this is a long line of text',
];
```

### In styling...
- Utilize root CSS variables (for colors, constants, etc.).
- Take advantage of SCSS syntax (use nested classes, `&` operator, etc.).
- Since SCSS is being utilized, avoid too much CSS classes.

## Backend

SOON™
