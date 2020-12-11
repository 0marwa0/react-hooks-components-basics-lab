# React Components Basics Lab

## Objectives

- Practice rendering static children components
- Have some fun with the rendered components in the browser

## Instructions

In this lab, we will be rendering a few children components in our top-most
component: `App`. All of our work will be done in `src/App.js`, the rest of the
components/source files shouldn't need any alterations.

Begin with `npm install`. Examine what is rendering in the browser
with `npm start`. You should see an error we need to fix!

In the labs throughout this section, we'll be working on building a small portfolio site in React.

Our goal for the first lesson is to get the basic components for our app -- the
`<Navbar>`, `<Home>`, and `<About>` components -- to be returned from the
`<App>` component.

Once we're done, we should get something like this:

<!-- demo image here -->

## Deliverables

- Two components, `<Navbar>` and `<Home>`, are already defined in the `App.js`
  file. Display both of these components as _child_ components of `<App>`.

- Create a third component, `<About>`. It should also be a child component of
  `<App>`. The `<About>` component should return a `<div>` with an id of
  `about`. The div can also optionally have some additional text content/other
  elements inside.

- Once the tests are passing, make sure to check out the result in the
  browser by running `npm start`!

## Resources

- [React Components](https://reactjs.org/docs/components-and-props.html)
