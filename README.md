# Proposal for Code Conventions

## Frontend

### In React code...
- Use hooks.
- Use Function Components as much as possible.
- Use named exports as much as possible.
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
- In creating functions inside components, use the arrow function syntax (to avoid confusion with the component's function).
- Resolve the warnings that are shown in the console as much as possible.

### In styling...
- Utilize root CSS variables (for colors, constants, etc.).
- Take advantage of SCSS syntax (use nested classes, `&` operator, etc.).
- Since SCSS is being utilized, avoid too much CSS classes.

## Backend

SOON™
