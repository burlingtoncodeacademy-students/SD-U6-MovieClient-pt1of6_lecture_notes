### Before Getting Started
There are two different branches associated with this lesson.
- Main
  - This branch provides the base notes of material not filled out.
- Completed
  - This branch includes all the added notes for you to review and compare with your own code-along.

### Topics Covered
- Reactstrap
- Auth & Signup Components

### What Should Already Be Understood
- Creating a React Application
  - File / Folder structure
- Reusable Components
- Props
- Basic structure of `useState`

## Files / Folders Provided in this Lesson
You will just need to spin up a new React application and add update the following:
This lesson starts right at the `npx create-react-app .` point.

This lesson also provides the solution for the **Counter Challenge** in the previous. The lesson will not walk through that solution, but the code is available to review.

- movies
  - src
    - components
    - `App.jsx`
      - *boilerplate code removed*
    - [App.css](./src/App.css) (provided code)

- `notes.md`: details the various notes taught throughout this lesson.
- **assets folder**:

## Resources
- [Reactstrap Docs](https://reactstrap.github.io/?path=/docs/components-forms--input#hidden-labels)
- [Bootstrap Grid](https://getbootstrap.com/docs/5.3/layout/grid/)
- [w3Schools useRef](https://www.w3schools.com/react/react_useref.asp)
- [Hook API Reference React](https://reactjs.org/docs/hooks-reference.html#useref)

## Challenge
**Login**
/* 
    - Create a login folder within auth.
        - Create a JSX file called login (consider how the file/folder should be set)
    - Create a functional component called Login
    - Setup a form:
        - Above the form, make an h2 that displays "Login"
        - Use components from Reactstrap (hint: consider Signup)
        - No labels are required.
        - Two input fields: 
            - email: use a placeholder to denote "Email"
            - password: use a placeholder to denote "Password"
    - Import useRef:
        - create variables to reference both email & password.
        - incorporate within the Input components
    - Handle Submit
        - Set the form to fire off an async function called "handleSumbit"
            - write is as an arrow function.
        - Within the function
            - console.log both useRef variables that were established.
    - Export the component.
    - Import & mount the Login component within Auth.jsx
        - Note: Frame the component in the same fashion as Signup.
*/