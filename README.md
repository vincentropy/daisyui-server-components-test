# react-daisyui-nextjs-server-components-test

This is a simple next project to test that daisyui works with nextjs server components.

## Steps to run

- `npm run dev`
- Main page should show a button with a green background

No "use client" directive is needed on the page that loads the Button component.
If desired, one can explicitly verify that the button is rendered on the server
by adding a log statement to the Button component code in the `node_modules/react-daisyui/dist/esm/Button/Button.js` file.
